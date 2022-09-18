<script>

let lastTaskId = 0

// List of activity 
// Each activity has a reference to a task 
// When work on that task was started and when 
// it ended. 
let workLog = [
    { taskId: 0, 
      start: 1663542930220,
      end: 1663542960745
    }
] 


// List of tasks that were worked on today
let tasks = [
    makeTask('dev', 'Start project'),
    makeTask('dev', 'Work on viewing tasks'),
]

function makeTask(category, description) {
    return {
        id: lastTaskId++,
        category,
        description,
    }
}

</script>

<main>
    <h1> Sloth </h1>
    <ul>
    {#each tasks as task}
    <li> {task.category}:{task.description} </li>
    {/each}
    </ul>
</main>

<style>
</style>
