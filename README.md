![jspsych logo](http://www.jspsych.org/7.0/img/jspsych-logo.jpg)

jsPsych is a JavaScript framework for creating behavioral experiments that run in a web browser.

## Plugin Description

The survey-likert plugin displays a set of questions with Likert scale responses, where the participant responds by selecting a radio button.

This version is modified to record the position of clicks on the page. This is done in page coordinates. It also records the position and width / height of the likert scale container element for comparison (so it's easy to determine the position of clicks relative to the scale).

The extra parameters produced are:

clicks
: all clicks in page coordinates {x:, y:}

likert_position
: the position and size {left:, top:, width:, height:} of the first Likert scale displayed, also in page coordinates

Tests unfortunately broken due to a module import path error.

## Examples

Several example experiments and plugin demonstrations are available in the `/examples` folder.
After you've downloaded the [latest release](https://github.com/jspsych/jsPsych/releases), double-click on an example HTML file to run it in your web browser, and open it with a programming-friendly text editor to see how it works.

## Documentation

Documentation for this plugin is available [here](https://www.jspsych.org/latest/plugins/survey-likert).

## Getting help

For questions about using the library, please use the GitHub [discussions forum](https://github.com/jspsych/jsPsych/discussions).
You can also browse through the history of Q&A on the forum to find related questions.

## Contributing

We :heart: contributions!
See the [contributing to jsPsych](https://www.jspsych.org/latest/developers/contributing/) documentation page for more information about how you can help.

## Citation

If you use this library in academic work, please cite the [paper that describes jsPsych](http://link.springer.com/article/10.3758%2Fs13428-014-0458-y):

de Leeuw, J.R. (2015). jsPsych: A JavaScript library for creating behavioral experiments in a Web browser. _Behavior Research Methods_, _47_(1), 1-12. doi:10.3758/s13428-014-0458-y

## Contributors

jsPsych is open source project with [numerous contributors](https://github.com/jspsych/jsPsych/graphs/contributors).
The project is currently managed by the core team of Josh de Leeuw ([@jodeleeuw](https://github.com/jodeleeuw)), Becky Gilbert ([@becky-gilbert](https://github.com/becky-gilbert)), and Björn Luchterhandt ([@bjoluc](https://github.com/bjoluc)).

jsPsych was created by [Josh de Leeuw](http://www.twitter.com/joshdeleeuw).

We're also grateful for the generous support from a [Mozilla Open Source Support award](https://www.mozilla.org/en-US/moss/), which funded development of the library from 2020-2021.
