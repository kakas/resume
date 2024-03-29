蕭錦成 (Hsiao, Chin-Cheng)

Full-Stack Web Developer

Taipei, Taiwan, shrimptrain@gmail.com

## Work Experience

### FARIA EDUCATION GROUP (May,  2021 - Present) 

**Full-Stack Web Developer**

- Develop and maintain the OpenApply system (https://www.openapply.com/) 
  - **Develop and Maintain Backend API**: Design, develop and maintain the backend API of the OpenApply application and optimize the code to improve readability and performance.
  - **Refactor the email template function**: Improve the readability and performance of the program, and support user-defined fields.
  - **Designed and developed an automated labeling system**: Designed and implemented an automated labeling system to effectively improve the efficiency of the corresponding processes.
  - **Introduce Coverband to remove dead code**: Introduced the Coverband tool to help identify and remove code that is no longer in use, improving code clarity and reducing redundancy.
  - **Developing 2FA functionality with devise-two-factor**: Improving App security.
  - **Performance optimization**:
    - Export function: 6.6 sec/request -> 3.8 sec/request
    - Student editing page: 10x faster on front-end, 2x faster on back-end
    - Optimize data sync API to increase response speed by 2.38 times, improving the efficiency of data synchronization.
  - **Technology Migration**:
    - Rails autoloader from classic to zeitwerk.
    - feature test toolchain from PhantomJS to selenium + headless chrome.
    - Successfully converted some pages to Vue2.js implementations for better program maintenance and reduced server load.
- Leadership and Training
  - **Lead program book clubs and Code Review clubs:** Organize and host professional skill enhancement activities to strengthen the team's professional knowledge.
  - **Mentoring junior developers:**  Lead junior developers to help them integrate into the team and familiarize with the workflow.
  - **Planning and Revision of Coding Style:** Lead the team to revise and plan the coding style to ensure the consistency of the coding style and improve the overall code quality.

### 幫你優 BonioO Inc. (Jan, 2017 - Present)

**Full-Stack Web Developer**

- Develop game-related functions.
   - Ruby on Rails and Rspec for the backend.
   - React and Redux for the frontend.
- Review Pull Requests, ensure business logic is correct and code quality is good.
   - From 2017/01/03 to 2021/01/31, our team issued 9008 PRs <sup>[1](#foot-note-1)</sup>, and 2979 PRs had reviewed by me <sup>[2](#foot-note-2)</sup>, it's about 33%.
- Build a WebSocket Server that can support 10k simultaneous connections.
   - Develop by Golang, and deploy to AWS Elastic Container Service.
   - High Available. (Some server shutdown will not affect the entire system.)
- Optimize the maintainability and performance of backend programs.
   - Add necessary DataBase index and remove unnecessary DataBase Index.
   - Fix or prevent the race condition.
   - Use design-pattern to increase readability and maintainability.
- Write JMeter scripts to perform load-testing.
   - Help my colleagues find the correct size of Infra for the online contest.
- Introduce Webpack so that the frontend can use ES6 syntax and babel-polyfill, making development faster and better maintained.
- Introduce React to develop game-related functions to make performance better, and let the development faster, maintenance easily.
- Import static-code-analysis tools for the frontend to reduce development time and increase maintainability.
   - ESLint + scss-lint
- Make game-related UI
   - Examples: https://github.com/kakas/resume/issues/1
- Organize program reading-club to improve professional knowledge of our team, and apply it to work.

### Freelancer (April, 2016 ~ Dec, 2016)

**Full-Stack Web Developer**

- Self-taught Ruby on Rails.
- Use Ruby on Rails to develop a loan and personnel management system. (Work on a piecework basis)

### 盈正豫順 Ablerex Electronics Co., Ltd. (Dec, 2011 ~ Mar, 2016)

**Firmware Engineer**

- Develop the 60 KVA three-phase uninterruptible power supply system.
   - Use C to develop on TMS320F2808 platform.
   - https://www.ablerex.com.tw/products_4.php?bgid=1&mgid=1&sgid=65
- Increase the parallel connection from 2 to 6, and increase the output power 3 times.
- Develop the 30 KAV three-phase uninterruptible power supply system with internal manual bypass for easy maintenance without power interruption.
   - https://www.ablerex.com.tw/products_4.php?bgid=1&mgid=1&sgid=37
- Make experiments in various environments.
   - In different voltages, loads, and temperatures.
   - Write test reports.
- Introduce git for version control. Make the codebase easy to maintenance.

## Education

National Kaohsiung University of Science and Technology, Master of Science, Department of Electrical Engineering, 2008 ~ 2010

National Kaohsiung University of Science and Technology, Bachelor of Science, Department of Electrical Engineering, 2004 ~ 2008

### footnote:

<a name="foot-note-1">1. Number Of PRs by our team</a>: Search `is:pr created:>2017-01-03` in Pull Requests list.

<a name="foot-note-2">2. Number Of Code Reviews</a>: Search `is:pr reviewed-by:kakas` in Pull Requests list.
