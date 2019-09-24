# 100 Days Of Code - Log

### Day 1: September 9, Monday, 2019  (Basic)
**Today's Progress**: basic code to start working. Creation of the repository. creation of the 100dasyofcode documentation. 

**Thoughts:** Only things have been installed. There have been no problems with this step. 

**Link to work:** [Commit Day 01](https://github.com/Gonzalo2310/i18nEdit/commit/e5f841458e55480bd0590200e6145c27544234f5)

### Day 2: September 10, Tuesday, 2019
**Today's Progress**: Research, learning and beginning of creation of a recursive folder reader. Folders of sample i18n files have also been added for testing.

**Thoughts:** The result and progress has been less than expected. The functionality that had to be developed is not complete yet. It is necessary to increase the concentration in the project. 

**Link to material added in samples** [Commit](https://github.com/Gonzalo2310/i18nEdit/commit/0bc3db3677861ee7f1bf43d9591f1cc7ab60963f)

**Link to work:** [Commit Day 02](https://github.com/Gonzalo2310/i18nEdit/commit/1e974f0047af59b112e86f2cbb02fc421696a54f)

### Day 3: September 11, Wednesday, 2019
**Today's Progress**: Alpha version of a recursive search function for folders and files. This functionality is the cornerstone of the whole further process.

**Thoughts:** Problems with promises. I have to practice them more. You get the expected results but you have to debug the process. 

**Link to work:** [Commit Day 03](https://github.com/Gonzalo2310/i18nEdit/commit/61d5dc1f12aa37c00a4a751ea4d7232428e30673)

### Day 4: September 12 - 13, Thursday - Friday, 2019
**Today's Progress**: The cycle that will mark the current and future evolution of the editor's capacity begins. This path is a little delicate and I lack knowledge.

**Thoughts:** Today we have returned a little to the frustration of mishandled promises. This is an important stumbling block at a time when I need agility.

**Link to work:** [Commit Day 04](https://github.com/Gonzalo2310/i18nEdit/commit/d616f64244e8795c6555fa2b9988a3ad9db0d6c2)

### Day 5: September 13, Friday, 2019
**Today's Progress**: Without success in the way of the previous day has changed strategy. In the end it's a good thing because the performance can improve that way.

The content that is not obtained immediately will be passed to obtain upon request in the use of the tree. This will avoid loading content that will never be used / consulted.

A "decent" visual result has been achieved. And it has been possible to verify that the function is recursive in a correct way.

**Thoughts:** Now I've got the bifurcated road. I must choose properly where to turn first. 
If I improve the existing code, create a system of variables for predefined values that later must be altered by the user or if I go ahead with the improvement of the object obtained from the result of the recursive function.

**Link to work:** [Commit Day 05](https://github.com/Gonzalo2310/i18nEdit/commit/020d3b1c4b22da237c293e145bc034bcf74e6e89)

### Day 6: September 14, Saturday, 2019
**Today's Progress**: Programmatic changes:
* Use of private variables in objects. 
* Functions to read and assign object properties. 
* Added UUID to uniquely identify each node.
* Independence of the UI. An intermediate function extracts data from the object to the ui. This allows a change from UI to future with less problems.

**Thoughts:** The concept of Objects in Js is a bit particular. It makes me uncomfortable not to offer aesthetic changes as if no changes had been made.
I'm thinking of a possible migration to TS in version 2.

**Link to work:** [Commit Day 06](https://github.com/Gonzalo2310/i18nEdit/commit/7b9de7151d117639ee9502a381b7d6df08d4f902)

### Day 7: September 15, Sunday, 2019
**Today's Progress**: Aesthetic Changes. Color of files and folders in the tree. Folders are sorted first.
Added a json with language codes. The next step is to organize each language separately.

**Thoughts:** The challenge now is to know how the languages are organized. 
The research led to 3 possibilities: In the names of the folders, in the names of the files or in the name of the root objects inside the files. This in JSON format.
The language can be only the country or also country-region.

**Link to work:** [Commit Day 07](https://github.com/Gonzalo2310/i18nEdit/commit/8ffe4caba6296bfa84c58b3bda3f1b742dd47ee1)

### Day 8: September 16, Monday, 2019
**Today's Progress**: The language recognition of each file has been started. This format is only 1/3 but will be used by the first alpha version.

**Thoughts:** We need to start migrating all requests and results to the Vue store. These steps should be well documented to allow easy future migrations.

**Link to work:** [Commit Day 08](https://github.com/Gonzalo2310/i18nEdit/commit/0f3b61c59f37405640889656b94d5f338f4ee336)

### Day 9: September 17, Tuesday, 2019
**Today's Progress**: The way of recognizing languages has been changed. And separated into two files (the region of a language (en-US / en -GB ) is an acronym for countries). 
Although there is only one call to the api, the logica has already been transferred to Vue's store. The variables will be used from there.

**Thoughts:** There is a possible bottleneck in the consultation of all languages and then each one individually. At this stage it may not be very relevant but for a final version it has to be adjusted.
We have already entered the loading of contents and parsing. This is another point that will evolve with the product

**Link to work:** [Commit Day 09](https://github.com/Gonzalo2310/i18nEdit/commit/f41448c8abcd73f3bbe86c6e305ae17c4f1df00c)

### Day 10: September 18, Wednesday, 2019
**Today's Progress**: Complicated day in the obligations. Little progress. Failed attempt to search the array of objects for the value chosen by the user.

**Thoughts:** Three main difficulties: Time, the logic of objects in Js and the type of response of the api. 

The response of the api and the objects could be otherwise but I follow that path because they are things I want to learn.

**Link to work:** [Commit Day 10](https://github.com/Gonzalo2310/i18nEdit/commit/6a981bdd5aeb6ef97d3925bae33517f3ad71c5c5)

### Day 11: September 19, Thursday, 2019
**Today's Progress**: I can't get out of the jam of the problem of the back objects replicated in the front. Change the path but the result is still not correct. Failure is part of the path of all creation.

**Thoughts:** I have the same problems as before. Lack of knowledge and practice

**Link to work:** [Commit Day 11](https://github.com/Gonzalo2310/i18nEdit/commit/2038c3fc4f0ede479a63fb82e3d4c7a3fdce77ba)

### Day 12: September 21, Saturday, 2019
**Today's Progress**: One day update delay because it was jammed. I wanted to learn too many things at once and there has been a very big knowledge gap. Regression and rewriting of part of the code to take it to a more familiar terrain. I have already stepped forward.

**Thoughts:** Rethink things more simply.

**Link to work:** [Commit Day 12](https://github.com/Gonzalo2310/i18nEdit/commit/b2b6ca3af69a63ffb62b41fc7d6408e41df782d8)

### Day 13: September 22, Sunday, 2019

**Today's Progress**: At last. The content of the file of the selected language is obtained. 
It's time to start assembling the project with a certain level of seriousness for others to test in a short time.

**Thoughts:** 
Construction of the UI.
Back restructuring.
Order of priorities changed.

**Link to work:** [Commit Day 13](https://github.com/Gonzalo2310/i18nEdit/commit/d541ef2b71556c0acbac766b583e80678b6a79fb)

### Day 14: September 23-24, Monday - Tuesday, 2019

**Today's Progress**: Improvements in the back. Start of UI. Implementation of locale. Delay of a few minutes of midnight mark as next day

**Thoughts:** 
Many changes applied. 
You have to think about design on paper.
Preparation on the march of the locale.

**Link to work:** [Commit Day 14](https://github.com/Gonzalo2310/i18nEdit/commit/7262bce2b3d50993c5bb393f1a5c70230b4adceb)

### Day 15: September 24, Tuesday, 2019

**Today's Progress**:A mini challenge has been developed in the frontend so that you can choose the UI framework to use without having to modify code.

**Thoughts:** 
* The vuetify library is giving a problem and will probably be changed for now.
* I always have time very close to midnight and some commit is not made on the day indicated by the schedule.

**Link to work:** [Commit Day 15](https://github.com/Gonzalo2310/i18nEdit/commit/636ce5f35c7d142c845b802b53a9fc5e40154d0a)