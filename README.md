README
======

    
    Copyright 2014 Lennox Corporation
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
        http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    

**Introduction** This is the source code for my application, "Launcher", available at:
   https://play.google.com/store/apps/details?id=com.lennox.launcher    

**Compiling** - The source is not immediately compilable for the following reasons:    

* **Libraries**: I have not yet released the source code for the library projects used. This will probably happen at a much later date, until then you will need to remove the projects dependencies on these libraries and provide replacements for any missing resources/methods which are crucial to the functionality.

* **Build System**: I build using Ant, which relies on some custom setup work in my build environment which is not publicly available. After sorting out the Library dependencies, you should be able to set up and compile using Eclipse/Ant/Android Studio by taking a little time to setup the appropriate build configs and following the error reports.

