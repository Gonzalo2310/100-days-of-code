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

### Day 16: September 27, Friday, 2019

**Today's Progress**: A day skipped involuntarily. The multiple UI system will be integrated in a "grotesque" way because it is not the purpose of this project but it will serve for proofs of concept and usefulness.
The next step is the assembly of the UI without functionality.

**Thoughts:** 
* Speed up the development of multiple UI so as not to delay in coding but to lose enthusiasm in the project.

**Link to work:** [Commit Day 16](https://github.com/Gonzalo2310/i18nEdit/commit/ffcf8dde41fe5170bcf4df8048e0506e86c31f02)

### Day 17: September 28, Saturday, 2019

**Today's Progress**: 've wasted some time with dynamic imports. I left it as a technical debt. 
As I move forward I have collided with the mistake of reading errors too quickly. A bad interpretation wasted my time. The UI advances. Today it was slow.
But no time has been wasted. There is a rearrangement of files. A better understanding of the idea to optimize it. And new unknowns have been discovered that need to be improved.

**Thoughts:** 
* The UI system has to move at a better pace.
* Dynamic loads must be optimized if more UI ibreries are to be included.
* The attempt with Vuetify failed and remains a technical debt.
* There is a validation code in InButton that must be improved before continuing.

**Link to work:** [Commit Day 17](https://github.com/Gonzalo2310/i18nEdit/commit/997e7e2e126a2b5aa7bbbeb9fd27f9051a305853)


### Day 18: September 29, Sunday, 2019

**Today's Progress**: Today there is not much concentration but a step has been taken. The UI advances and soon it will be complete and I will move to my favorite place: Functionalities.
Phrase for today: The continuous aesthetic improvement of something that still doesn't work can be a symptom of fear of taking the next step.

**Thoughts:** 

We continue with the same difficulties as the day before.

**Link to work:** [Commit Day 18](https://github.com/Gonzalo2310/i18nEdit/commit/4e1f1f2dd21ba5ecd63756e6f2e2435421e21fca)

### Day 19: September 30, Monday, 2019

**Today's Progress**: I have days repeating the same kind of progress. Sorry about the boredom.
More UI creation. Surely the whole week will be more or less the same.
I think that before the 30 days I will be able to share material for those who want to try things.

**Thoughts:** 
Idem

**Link to work:** [Commit Day 19](https://github.com/Gonzalo2310/i18nEdit/commit/29e7cdec862d935e0df935bc63084d7269e4c321)

### Day 20: October 1, Tuesday, 2019

**Today's Progress**: Another step has been added to the UI. Tired of drawing views now I will start to make them useful (One in special I have no idea how to do it).

Tip: Don't worry, what we've been programming for a while we also see that everyone else has super fantastic ideas and ours seems small next to it.

Tip: Use a time trial for tasks. It helps a lot not to disperse.

**Thoughts:** 
* I'll move on to functionality on the UI created because I'm a little bored with design.
* Now that there are elements of the multiple UI would have to optimize the operation.
* I am faced with another interesting but unknown functionality: Tree of files.

**Link to work:** [Commit Day 20](https://github.com/Gonzalo2310/i18nEdit/commit/1ae4dd49c857da24c7ca05397496c2f408a647ed)

### Day 21: October 2, Wednesday, 2019

**Today's Progress**: It's been a busy day. But that's what the challenge is all about. To find the moment. The basic UI is finished. 
It still remains to modify the type of load of elements and make it more dynamic (I would be ashamed to show it so). 

**Thoughts:** 
The main problem of the month of October  is the time. At least until the online conference on the 12th.

**Link to work:** [Commit Day 21](https://github.com/Gonzalo2310/i18nEdit/commit/dac0468eff57fa6ef148e32b67de3d3bc0f15195)



### Day 22: October 4, Friday, 2019

**Today's Progress**: I don't have a good rhythm and that must change or I won't advance properly. Things to do that take up my time are a lot like excuses.

**Thoughts:** 
Intense week and short periods of time. It is necessary to perfect the organization.

**Link to work:** [Commit Day 22](https://github.com/Gonzalo2310/i18nEdit/commit/827fdd8955bf8f4e4031cb97212c98618b5d0209)

### Day 23: October 5, Saturday, 2019

**Today's Progress**: Advance of backend processes. creation of project file. Now every step and action will have footprint on that file. (each action? we'll see)

**Thoughts:** 
* Today's process has been something without content controls or double existence. 
* We have to do those controls and then take the next step.
* The project has few forms but we have to leave them solid.

**Link to work:** [Commit Day 23](https://github.com/Gonzalo2310/i18nEdit/commit/c19872bfdda1c0ce5084be83388b7dee60e023da)


### Day 24: October 6, Sunday, 2019

**Today's Progress**: It hasn't been a great update but I'm starting a "delicate" way of managing files.
Slight progress was made. 
There will be no more updates on Sundays.

**Thoughts:** 

* Many controls are missing. 
* Slight progress due to lack of knowledge.
* Day without much inspiration

**Link to work:** [Commit Day 24](https://github.com/Gonzalo2310/i18nEdit/commit/6ab9cdee05bec0d442d6cf716f59d36bb88d0904)

### Day 25: October 14, Monday, 2019

**Today's Progress**: I had to stop the project for a week due to work overload.
We have come back and continue with the following changes: 

* Back: 
  * The use of hidden functions and fields in the tree object was eliminated.
  * The object tree and tree-ui have been rewritten.
* Front:
  * The secondary project Multi UI was removed to keep the focus.
  * The store of Vuejs has been modified to modular mode.
  * A global configuration of Axios with interceptors for error control has been created.
  * The components have been rewritten adapting them to a single UI (element-ui).
  * 3 scss (desktop, tablet and mobile) have been added to perform the responsive when the time comes.

**Thoughts:** 

* We're back to fighting promises.
* Organization.
* Focus (stop creating ramifications of the original idea before finishing the main thing)

**Link to work:** [Commit Day 25](https://github.com/Gonzalo2310/i18nEdit/commit/63d50c44fa9813d044a8a87b06888f61c525fa47)



### Day 26: October 16, Wednesday, 2019

**Today's Progress**: We have started to create the configuration file with the specific data of the project.

This is important in order to keep the project created with the program up to date. 

**Thoughts:** 

* Time

**Link to work:** [Commit Day 26](https://github.com/Gonzalo2310/i18nEdit/commit/807c673ebc3650ead7beb60f4a4a08c0a06ff17d)



### Day 27: October 17, Thursday, 2019

**Today's Progress**: Made a 50% of the module of choice of work folder.

**Thoughts:** 

* Time

**Link to work:** [Commit Day 27](https://github.com/Gonzalo2310/i18nEdit/commit/7d260497b989ebc9dfab84d58379ed4393bf46e6)



### Day 28: October 17, Friday, 2019

**Today's Progress**: Almost complete the folder explorer (80%).
Wanting to complete the configuration of the project to make functionalities (there is still a step of global configuration)

**Thoughts:** 

* I need a roadmap
* Setting goals and deadlines

**Link to work:** [Commit Day 28](https://github.com/Gonzalo2310/i18nEdit/commit/0f6227ac52e882bb720211f410bd4f447a876707)