# @jspsych/plugin-video-keyboard-response

## 1.0.0
### Major Changes



- [#2183](https://github.com/jspsych/jsPsych/pull/2183) [`c8760b1`](https://github.com/jspsych/jsPsych/commit/c8760b19483453b0e77dc98e464e1629b5605a15) Thanks [@jodeleeuw](https://github.com/jodeleeuw), [@becky-gilbert](https://github.com/becky-gilbert), [@bjoluc](https://github.com/bjoluc)! - **jsPsych is now fully modular, with individual NPM packages for the core library, plugins, and extensions.**
  
  To support this change, we've made a number of breaking changes. We've added [a guide for migrating from version 6.x to 7.x](https://www.jspsych.org/7.0/support/migration-v7/) to the documentation, and updated the [hello world tutorial](https://www.jspsych.org/7.0/tutorials/hello-world/) with instructions for configuring jsPsych in three different ways. In addition to enabling package management, some of the benefits that this change provides include an improved developer experience with IntelliSense code hints, proper encapsulation of jsPsych so that multiple instances can be run on the same page, and easier integration with modern JavaScript tools like bundlers.

### Patch Changes



- [#1533](https://github.com/jspsych/jsPsych/pull/1533) [`7b16a1d`](https://github.com/jspsych/jsPsych/commit/7b16a1d) Thanks [@becky-gilbert](https://github.com/becky-gilbert)! - Fixed a bug that caused the trial to not end when the `trial_ends_after_video` parameter was set to `true` and the video ended at a specific time via the `stop` parameter.



- [#2192](https://github.com/jspsych/jsPsych/pull/2192) [`2883e421`](https://github.com/jspsych/jsPsych/commit/2883e4211dbf8c6bb5cf291289ff2e3f82252032) Thanks [@becky-gilbert](https://github.com/becky-gilbert)! - Fix implementation of `start` parameter in `video-*` plugins so that it works in iOS/MacOS browsers.

- Updated dependencies [[`37b85f95`](https://github.com/jspsych/jsPsych/commit/37b85f953c803e1cca80d8e5275be948d375e2f2), [`37b85f95`](https://github.com/jspsych/jsPsych/commit/37b85f953c803e1cca80d8e5275be948d375e2f2), [`37b85f95`](https://github.com/jspsych/jsPsych/commit/37b85f953c803e1cca80d8e5275be948d375e2f2), [`37b85f95`](https://github.com/jspsych/jsPsych/commit/37b85f953c803e1cca80d8e5275be948d375e2f2), [`37b85f95`](https://github.com/jspsych/jsPsych/commit/37b85f953c803e1cca80d8e5275be948d375e2f2), [`37b85f95`](https://github.com/jspsych/jsPsych/commit/37b85f953c803e1cca80d8e5275be948d375e2f2)]:
  - jspsych@7.0.0
