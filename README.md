# Skill-Template
Each repository in [MistySampleSkills](https://github.com/MistySampleSkills) is an individual skill for Misty. This repository is a template for creating and contributing your own skills.

## Misty's Skills

A skill is an application you develop for the Misty platform. You can write skills for Misty using her REST API or her on-robot JavaScript API. This template shows the file structure for skills that run locally on Misty and use her on-robot JavaScript API. For more about skills, see [Introduction to Skills](https://docs.mistyrobotics.com/docs/skills/introduction/) in the documentation.

At their most most basic, on-robot skills require two files:
* a .js code file with the code to execute in the skill
* a .json meta file with information that enables Misty to understand what the skill does and how to execute the code

### Uploading a Skill

To upload a skill to your robot, compress the code and meta files into a .zip archive. Upload the compressed file to Misty using her [REST API](https://docs.mistyrobotics.com/docs/reference/rest/#saveskilltorobot).

### Assets

Some skills use image or audio assets that a user will need to upload to Misty before executing the skill. You can make these files available by placing them in your skill's repository, at the same directory level as your code and meta files.

### Code for Other Devices

Misty's skills can interact with code that executes on an Arduino, in your web browser, on a Raspberry Pi, or from other kinds of external devices. Consider including _all_ of this code in the repository for a skill. 

### Writing your README

It's good practice to include a README.md in the top level directory of a skill repository. The README.md for a skill might include a description of the skill, instructions on how to use the files in the repository, and any other information a user needs to know about using or contributing to the skill. This **Skill-Template** repository includes the following:
* **skill-template.js** - The code file for the skill-template sample skill.
* **skill-template.json** - The meta file for the skill-template sample skill.
* **skill-template.zip** - A .zip archive with the code and meta files for the skill-template sample skill. Upload this file to Misty to run the skill-template skill on your robot.
* **LICENSE** - License information for the files in this repository.
* **README.md** - Information about using this skill and contributing to this repository.

### Docs & Community

Check out [Misty's documentation](https://docs.mistyrobotics.com/) for more information about developing skills. And be sure to join the [Misty Community](https://community.mistyrobotics.com/) for discussions about Misty skill development and robotics in general!

***Note:** Skills contributed to [MistySampleSkills](https://github.com/MistySampleSkills)  by members of the Misty Robotics organization use the [Apache License](http://www.apache.org/licenses/LICENSE-2.0), but we encourage you to choose your own license for the skills that you create.*

