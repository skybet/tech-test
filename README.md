# Sky Betting & Gaming PHP & Frontend Technical Test

## Introduction

Welcome to the Sky Betting & Gaming Technical Test!

We hope that you find this exercise fun. There are no trick questions; we want to see your solution to a simple problem with well thought-out and well structured code.


## The Brief

The aim of the test is to produce a system capable of loading, modifying and saving some data using PHP, HTML and JS. You should use best­practices where appropriate, ensuring that you separate your presentation and logic and that your code is modular where possible.

You should fork this repository, commit your files, then submit pull requests as your submission.


## Step 1: MVC Form Handler

Make a simple MVC application from scratch to process posted form data, saving it to file and reading it back out again in order to update the records.

* Make a branch named `step1`
* The application structure is of your choosing, and the entities should be modelled appropriately
* The [form markup](markup.html) is provided in this repository and, as it stands, doesn't submit to anywhere; use it to create your view
* For storage, you should write the data in a suitably encoded format to 'data.txt' or similar on disk
* The form fields should be repopulated from the data file when the page loads, or following a save operation

To complete this step, extend your system to support a new `jobtitle` field, which will be populated for at least some of the records.

Add appropriate unit tests using [PHPUnit](https://phpunit.de/).


## Step 2: Asynchronous Loading and Saving

The brief for this step is to replicate the functionality of Step 1, but achieve the load and save operations asynchronously from the browser, transferring a JSON structure to represent the data back to the server.

* Make a new branch named `step2` — branched from `step1` above
* You should aim to use [`php://input`](http://php.net/wrappers.php#wrappers.php.input) to receive the POST body
* Develop the code for a modern browser of your choice, and let us know what it has been tested in


## Implementation Notes

* Use of PHP frameworks is discouraged
* For the client-side element you can use your own JavaScript or base it on an open source framework
* Using [Composer](https://getcomposer.org/) for autoloading, tactical libraries & PHPUnit is allowed

Don't worry if you don't finish all of the steps; we're more interested in how you implement the steps which you do complete as they give us more insight into how good you are as a developer.

Remember to *Sell Yourself*!


## Form Markup

An example of the initial HTML form is [provided in this repository](markup.html).
