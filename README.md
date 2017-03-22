# FiskCoursesGraphs
Dependency Graph of Fisk University Courses per Department


In order to address the difficulties that students have when deciding which courses to choose after having taken a given course, a simple visualization tool that displays a graph of courses that students must take to fulfill requirements is offered as a solution. The tool abstracts courses and their prerequisites with a Directed Acyclic Graph where the nodes are courses and the links indicate the order in which courses have to be taken by the student. Essentially instead of dealing with a simple balance sheet, students now have at their disposal a web application from which they can see courses and prerequisites, which are topologically sorted. The tool also allows students to select a course and view how it relates topologically to other required courses. The tool is written primarily in d3.js, JQuery, HTML and pure JavaScript.
