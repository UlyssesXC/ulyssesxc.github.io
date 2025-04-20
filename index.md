---
title:  👋
---
## Hi, I’m Xiangchao(Chase) Chen
<div style="display: flex; align-items: center; gap: 24px; flex-wrap: wrap; margin-bottom: 2em;">

<img class="intro-photo" src="/assets/images/profile.jpg" alt="Xiangchao Chen"
  style="width: 180px; height: auto; object-fit: contain; border-radius: 0 !important; box-shadow: none !important;" />

  <div style="flex: 1; min-width: 250px;">
    <p style="margin: 0;">I'm currently a Master of Engineering student in ECE at Western University.</p>
    <p>I have a strong interest in Embodied Intelligence, particularly in its research foundations and real-world applications.</p>
    <p><strong>I'm actively seeking opportunities for research assistant positions or PhD programs in this exciting field.</strong></p>
  </div>

</div>


{% include button.html text="Github" icon="github" link="https://github.com/UlyssesXC" color="#B0C4DE" %} {% include button.html text="Twitter" icon="twitter" link="https://twitter.com/" color="#0d94e7" %} {% include button.html text="Resume 👨🏻‍💻" link="https://github.com/" color="#5F9EA0" %} {% include button.html text="Email" icon="email" link="xche683@uwo.ca" color="#00BFFF" %}

### EDUCATION
##### Western University
> M.eng in Electrical and Computer Engineering

##### Hangzhou City University (Formerly: Zhejiang University City College)
> First（2018） and Third（2019） Prize in TI Cup National Undergraduate Electronic Design Contest

> Achieved high marks in core technical courses, including Microcontrollers (96), C (89), C++ (90), Mobile Communications (91), and Circuit Principles (91)

### EXPERIENCE
#### Weixun Nairui Intelligent Technology (Hangzhou) Co., Ltd.
Team leader / Full Stack Engineer, Technology Department Aug 2023 – Aug 2024

 Led a cross-functional team in developing an industrial inspection robot, achieving a manpower reduction
of 60-80% in three TTI downstream factories within 2 months of product launch. Responsibilities included
supply chain communication, system development.

 Independently led the majority of the robot's system development, including: PLC, power circuitry,
optical imaging design, Linux PyQT interface & master control, database management, and Fanuc
robotic arm motion control.

 Collaborated with a team to develop an image recognition algorithm for the robot by establishing dataset
standards, collecting and organizing datasets, and implementing YOLO v8 for visual detection.

#### Nokia Shanghai Bell Co., Ltd.
Embedded Software Engineer, NSB MN RAN R&D L1 Department Aug 2021 - Feb 2022

 Implemented and tested 5G/NR algorithms such as FFT and MIMO on ASIP prototypes. Focused on
evaluating ASIP performance and performance enhancement of algorithm functionality.

 Participated in the migration and optimization of code logic from x86 to ARM architecture for 5G/NR
RAN Layer 1. This includes leveraging NEON instruction sets for performance optimization, enhancing
memory access and data caching efficiency, and adapting low-level hardware interfaces.

 Conducted 5G/NR RAN Layer 1 functionality testing, refinement, and development of product code logic
within x86-based simulation environment.

#### Tuya Inc. (NYSE: TUYA)
Embedded Software Engineer Intern, Software Development Department Dec 2019 - Jul 2020

 Participated in the development of IoT-SDK for IoT products utilizing protocols like WIFI, Bluetooth,
and Zigbee. Main responsibilities included assisting in SDK development and deployment.

 Engaged in client projects using IoT chips, primarily focusing on various home appliances and industrial
IoT applications. Organized more than 100 pages of engineering documents during this period.

### As a Jekyll theme

1. Add `gem "alembic-jekyll-theme"` to your `Gemfile` to add the theme as a dependancy
2. Run the command `bundle install` in the root of project to install the theme and its dependancies
3. Add `theme: alembic-jekyll-theme` to your `_config.yml` file to set the site theme
4. Run `bundle exec jekyll serve` to build and serve your site
5. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

### As a GitHub Pages remote theme

1. Add `gem "jekyll-remote-theme"` to your `Gemfile` to add the theme as a dependancy
2. Run the command `bundle install` in the root of project to install the jekyll remote theme gem as a dependancy
3. Add `jekyll-remote-theme` to the list of `plugins` in your `_config.yml` file
4. Add `remote_theme: daviddarnes/alembic@main` to your `_config.yml` file to set the site theme
5. Run `bundle exec jekyll serve` to build and serve your site
6. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

### As a Boilerplate / Fork

_(deprecated, not recommended)_

1. [Fork the repo](https://github.com/daviddarnes/alembic#fork-destination-box)
2. Replace the `Gemfile` with one stating all the gems used in your project
3. Delete the following unnecessary files/folders: `.github`, `LICENSE`, `screenshot.png`, `CNAME` and `alembic-jekyll-theme.gemspec`
4. Run the command `bundle install` in the root of project to install the jekyll remote theme gem as a dependancy
5. Run `bundle exec jekyll serve` to build and serve your site
6. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

## Customising

When using Alembic as a theme means you can take advantage of the file overriding method. This allows you to overwrite any file in this theme with your own custom file, by matching the file name and path. The most common example of this would be if you want to add your own styles or change the core style settings.

To add your own styles copy the [`styles.scss`](https://github.com/daviddarnes/alembic/blob/master/assets/styles.scss) into your own project with the same file path (`assets/styles.scss`). From there you can add your own styles, you can even optionally ignore the theme styles by removing the `@import "alembic";` line.

If you're looking to set your own colours and fonts you can overwrite them by matching the variable names from the [`_settings.scss`](https://github.com/daviddarnes/alembic/blob/master/_sass/_settings.scss) file in your own `styles.scss`, make sure to state them before the `@import "alembic";` line so they take effect. The settings are a mixture of custom variables and settings from [Sassline](https://medium.com/@jakegiltsoff/sassline-v2-0-e424b2881e7e) - follow the link to find out how to configure the typographic settings.
