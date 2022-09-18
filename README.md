# Sloth 

This is a project to track how time is spent while working on various 
projects. It is too easy for me to think that I am working harder and
longer than I am actually am. This tool should make it easy to 
track work activity and how time is spent by category. This feedback
should also be used to better plan my day. 

A day is divided into a list of logged activity. Each activity 
log has a reference to a task, when it was started and when it 
ended. There is also a list of tasks that are added to as the
day progresses. Starting a new task stops the previous task, 
adds that task to the activity log and then starts the new one.

The backend when it is written will be written in Go. Because I am 
the only intended user, I will use sqlite for persitent storage. I 
will also store usage in the browser for offline use.

While working on this, I will keep a notepad of pencil and paper
so that I can get the workflow down. This will also make it easier
to workon other parts of the app in any order that makes sense.

I plan to work on this project for at least a month but up to a year.
I plan to really polish it so that I can use it when I am searching
for a job in a year or so. I also intend to really polish it because,
I want it to be nice to use.

## TODO 

Managing Tasks
- [ ] Add a way to view the tasks 
- [ ] Add a way to add tasks
- [ ] Add a way to edit tasks
- [ ] Add a way to delete tasks
  - [ ] B/C the activity log contains a reference to a task,
  we can only delete tasks for which there are no activity ogss

Tracking Activity 
- [ ] Create a way to start a task
- [ ] Create a way to stop a task
- [ ] Create a way to view the activiy log

Visualizaation
- [ ] Create a way to view tasks graphically
