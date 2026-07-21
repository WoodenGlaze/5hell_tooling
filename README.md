# 5hell_tooling
Some tools I use w 5hell to ensure consistency

## 5hell_tests.src
### 5hell_tests.src build instructions and usage:

##### in-game:
Preparations:
 - [ ] /root/src has all the 5hell .src files
 - [ ] /root/src contains 5hell_tests.src
 
 1. Build 5hell like normal, put the binary in /root (ie: /root/5hell)
 2. Build 5hell_tests.src, put the binary in /root (ie: /root/5hell_tests)
 3. run 5hell
 4. in 5hell, run 5hell_tests [args] (see below)
 
 ##### vscode:
Preparations:
 - [ ] 5hell cloned
 - [ ] 5hell_tests.src created in the same folder, with the contents copied over
 
 1. Build 5hell like normal (Right click 5hell.src, Build file from context)
 2. Build 5hell_tests.src (Right click 5hell.src, Build file from context)
 3. run 5hell
 4. in 5hell, run 5hell_tests [args] (see below)
 
 
 ### commandline args:

<pre>
 // --keep | keep the test artifacts in home directory after run
 // --runtime-smoke | run runtime smoke tests for original commands/globals/privates
 // --expect-scp-file-destination | expect patched scpm behavior for destination filename handling
 //  (otherwise, baseline-compatible(4.3.9) behavior is accepted as passing) (**Will be removed in future versions)
 // --only [substring] | only run/list tests whose name contains substring (repeatable; OR'd together)
 // --list | print the (possibly --only filtered) test plan and exit without running anything
 // --unsafe | also run tests that touch real, persistent, non-sandboxed game state
</pre>

## Credits:
<pre>
 Plu70: For making the awesome tool 5hell, and being a cool dude.
 Get your 5hell here:
 https://github.com/jhook777/5hell-for-Grey-Hack-the-Game

 Add Marinette by not_s0phie to it aswell!:
 https://github.com/shippingfandom/Marinette
 it has saved me so much time, and is just an awesome project!
</pre>