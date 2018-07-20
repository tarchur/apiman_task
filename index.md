## Apiman task

### Tools
- I used linux tools for this task.
- I used docbook to create the source file, then pandoc to generate the PDF.
 - I used the default stylesheet, so the PDF looks like a standard LaTex document.
 - Also, the fonts  for console input and output were not the same as the Red Hat fonts.
- I edited the docbook file using vim , on a Fedora 28 Workstation platform.

### Research

- The configuration steps were described thoroughly in [crash course in apiman](http://www.apiman.io/latest/crash-course.html#_getting_the_bits_downloading_apiman)
 - The command to clone the apiman quickstarts did not work for me, so I looked for the GitHub site for api-quickstarts and tried a different command:
   - Command in Crash Course link: git clone git@github.com:apiman/apiman-quickstarts.git
   - Command that I successfully executed: git clone https://github.com:apiman/apiman-quickstarts.git
- It was not always obvious in online apiman documents which version of apiman they referred to. So some of the instructions are invalid. One source indicated that the apiman quickstarts apis are preconfigured in apiman; they are not, for the version I installed.

### Structure of instructions for Configuration

- I created a  list of short instructions to provide an overview of the configuration, and added the detailed instructions in separate subsections. I did this because I find that I sometimes lose track of where I am in a long document where the steps contain all the execution details.
- Normally, I would chunk lists into smaller sublists, but for this first attempt, I wanted the instructions at the same level, to reflect the subsequent subsections being at the same heading level. I would probably revisit this decision, however, and either divide the list into smaller lists, or nest some items as (a), (b).
<!--**Bold** and _Italic_ and `Code` text
[Link](url) and ![Image](src)-->


