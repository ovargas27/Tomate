# Tomate

Tomate is a pomodoro tool to help me to organize my time and work

## Specifications / TODOs
  Tasks

  + User can create tasks
  + _Task's description have a limit of 120 characteres_
  + One task should have one of this states: *unstarted*, *incomplete* or *finished*
  + One task should have one or more pomodoros (unless is *unstarted*)

  Pomodoros

  + When a task is started one pomodoro is created.
  + Every pomodoro should have description, the default is task's description
  + _Pomodoro's description have a limit of 120 characteres_
  + Pomodoro's length could be: *small(10 mins)*, *medium(15 mins)* or *normal(25 mins)*
  + Default length is normal
  + When a pomodoro time finish, task's state should change to *finished* or *incomplete*
  + When a pomodoro time finish, the user should write a note (one 'done' is good enough)
  + A task can start many times until is *finished*
  + _User can add notes even if the pomodoros is not finished_

Notes:

  +  Every notes should have an owner (pomodoro)

> specifications in _italics_ are optionals

## RDD

This is a RDD based project. If you want know more, visit [Readme Driven Development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html)
