Django quiz app
===============

This is a configurable quiz app for Django.

I use it to run a few medical revision websites. Here is an [example website](http://www.revisemrcp.com/)

My websites have used twitter bootstrap for the front end and I have tried to strip out anything from 
the template files that are dependant on bootstrap.

This is a major work in progress.

Current features
----------------
Features of each quiz:
* Question order randomisation
* Storing of quiz results under each user
* Previous quiz scores can be viewed on category page
* Correct answers can be shown after each question or all at once at the end
* Logged in users can return to an incomplete quiz to finish it

Multiple choice questions
* Questions can be given a category
* Success rate for each category can be monitored on a progress page
* Explanation for each question result can be given


It was developed using Django 1.4.1. 

This is my first open source project so please forgive any problems and/or dreadful code!

MIT License (MIT)
Copyright (c) 2013 Dr Tom Walker

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
