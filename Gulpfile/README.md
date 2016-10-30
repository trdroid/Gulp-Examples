# Gulpfile

A typical way of writing a gulpfile is by including Plugins/NodeJS-Modules that can be used in the tasks.

**Obtaining Plugins/NodeJS-Modules**

Use *npm* to obtain the required Plugins/NodeJS-Modules prior to using them in the gulpfile. 

**Chaining**

Each Plugin/NodeJS-Module ideally provides a single-purpose action, 
which can be chained with other Plugins/NodeJS-Modules to perform complex operations on the data.

### Gulp API Methods

The Gulp API methods are the building blocks of a gulpfile.

Gulp initially offered the following four methods

* *.task()*
* *.src()*
* *.watch()*
* *.dest()*

The 4.0 release offered the following additional methods

* *.series()*
* *.parallel()*

### *.task()* method

The *.task()* method is used to define a new task.

```javascript
.task(<name of the task>, <function to execute on running the task>);
```

### *.src()* method


### *.watch()* method


### *.dest()* method

The *.dest()* method is used to specify the output destination of the processed file. 

### *.parallel()* method


### *.series()* method

