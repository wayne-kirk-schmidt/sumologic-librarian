Sumo Logic Librarian
====================

Want to explore your Sumo Logic environment, but not quite sure where to start? 

Sumo Logic is the solution for you!

Relying on accounting activity you enable to provide "Sumo Logic on Sumo Logic" 
providing insights into how your organization is using data it ingests.

Installing the Content!
=======================

    1. You will need to turn on specific policies.

'''
       *   Administration -> Account -> Data Management
           *   Enable the data volume to turn on accounting information on the data being ingested.
       *  Administration -> Security -> Policies
           *   Enable both the policies in "Sumo Logic Auditing" section
               *   Enable Audit Records
               *   Enable Search Audit Records
'''

    2. Once this is done, then navigate to your library

    3. View the raw contents of the JSON file. Copy the complete contents of the JSON file.

    4. Navigate to the library and locate a folder you want to install this in.

    5. Choose "Import" from the right option list from the folder you chose.

    6. This will bring up an input panel with two inputs, a name and JSON content.

    7. Type in the name "Sumo-Logic-Librarian" into the name of the content

    8. Then paste the JSON file contents into the payload section
 
    9. Click on save, and then refresh the page. You should be ready to use the Librarian!


License
=======

Copyright 2020 Wayne Kirk Schmidt
https://www.linkedin.com/in/waynekirkschmidt

Licensed under the Apache 2.0 License (the "License");

You may not use this file except in compliance with the License.
You may obtain a copy of the License at

    license-name   APACHE 2.0
    license-url    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Support
=======

Feel free to e-mail me with issues to: 

+    wschmidt@sumologic.com

+    wayne.kirk.schmidt@gmail.com

I will provide "best effort" fixes and extend the scripts.
