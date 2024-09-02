# Gym Tracker webapp

## What is this?

* Webapp to track exercises done @ gym. 

### Basic components & functionality

* Add new [exercises](####Exercises)

* Modify existing exercises

* Delete existing exercises

* Add new [training days](####Training-Day)

* Modify existing training day

* Delete existing training day

* Daily view of exercises

* Monthly view of training days


#### Exercises

* Basic piece of info. 

* Contains: title, series, reps/series, comment.

```
title: text
series,reps/series: array of tuples of int,int
comment:text
```

#### Training Day

* Container of exercises. 

* Restrictions: Can be empty on creation. Cannot be empty on save.

* Contains: title, exercises, comment.

```
title: date
exercises: array of exercises
comment:text
```

## Why do I need this?

* Because I don't want to intall any crappy app into my phone. 

## How am I building this?

* MERN stack. Basically MongoDB to store the data. ExpressJS for routing. React for frontend (and because I want to practise). NodeJS for server-side.

* Nvim as editor.

* Will try to host the webapp in my WSL instance in my laptop.
