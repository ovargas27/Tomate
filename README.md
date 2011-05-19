# Tomate

Tomate is a pomodoro tool to help me to organize my time and work

## Specifications / TODOs
  Tasks

  + User can create tasks
  * Task's description have a limit of 120 characteres
  + One task should have one of this states: _unstarted_, _incomplete_ or _finished_
  + One task should have one or more pomodoros (unless is _unstarted_)

  Pomodoros

  + When a task is started one pomodoro is created.
  + Every pomodoro should have description, the default is task's description
  * Pomodoro's description have a limit of 120 characteres
  + Pomodoro's length could be: _small(10 mins)_, _medium(15 mins)_ or _normal(25 mins)_
  + Default length is normal
  + When a pomodoro time finish, task's state should change to _finished_ or _incomplete_
  + When a pomodoro time finish, the user should write a note (one 'done' is good enough)
  + A task can start many times until is _finished_
  * User can add notes even if the pomodoros is not finished

Notes:

*  Every notes should have an owner (pomodoro)

> This is a RDD based project. If you want know more, visit [Readme Driven Development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html)
