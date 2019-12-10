<div id="header" class="row">
  <div class="col-xs-12 col-sm-9 col-md-9 col-lg-10">
    <h1>Ben Flannery</h1>
    <h2>Software Engineer <br><small>Lexington, KY</small></h2>
  </div>
  <div class="col-xs-12 col-sm-3 col-md-3 col-lg-2 contact well well-sm">
    <ul class="row fa-ul">
      <li class="fa fa-envelope col-xs-3 col-sm-12 col-md-12 col-lg-12"><a href="mailto:ben.flannery@gmail.com"> email</a></li>
      <li class="fa fa-desktop col-xs-3 col-sm-12 col-md-12 col-lg-12"><a href="http://oflannabhra.com"> web</a></li>
      <li class="fab fa-github col-xs-3 col-sm-12 col-md-12 col-lg-12"><a href="http://www.github.com/oflannabhra"> GitHub</a></li>
      <li class="fa fa-phone hidden-xs col-sm-12 col-md-12 col-lg-12 tel">(859) 338-3460</li>
      <li class="far fa-file col-xs-3 col-sm-12 col-md-12 col-lg-12 pdflink"><a href="resume.pdf"> PDF</a></li>
    </ul>
  </div>
</div>
<hr class="hidden-xs">
<div id="profile" class="row">
  <h3 class="col-md-3">Profile</h3>
  <div class="col-md-9 content">
    <p>
      I am a Software Engineer with over 9 years of experience, across a variety of domains including application, native mobile, API backend, firmware, and networking protocol design.
    </p>
    <p>
      My career has been marked by an ability to quickly pick up whatever technology or skills the business needs have dictated, to work well within any team, and to introduce modern development practices wherever I've been.
    </p>
    <p>
      I'm seeking a position at an engineering-forward company that utilizes industry-leading best practices, and which provides a technical career progress track.
    </p>
  </div>
</div>
<hr>
<div id="skills" class="row">
  <h3 class="col-md-3"> Skills </h3>
  <div class="col-md-9 content">
    <h4> Languages </h4>
    <ul>
      <li> <strong>Swift:</strong> Versions 2.0 to 5.1. Multiple products shipped and live on the App Store</li>
      <li> <strong>Objective-C:</strong> Objective-C since before ARC, multiple products shipped.</li>
      <li> <strong>C/C++:</strong> For firmware developement, running on tens of thousands of devices.</li>
      <li> <strong>PHP:</strong> Version 5.5 to 7.3. Backend API development and content management systems.</li>
      <li> <strong>Javascript:</strong> Used in all front-end development I have done.</li>
    </ul>
    <h4> Frameworks / Tooling </h4>
    <ul>
      <li><strong>iOS:</strong> UIKit, CoreData, MapKit, Interface Builder & AutoLayout, XCTest, fastlane</li>
      <li><strong>Web:</strong> Laravel, Lumen, Ruby on Rails, AWS</li>
      <li><strong>Firmware/Embedded:</strong> FreeRTOS, TouchGFX, STMCube, gcc, IAR</li>
      <li><strong>Networking / Protocols:</strong> Bluetooth, Thread, HTTP, IP, TCP & UDP
      <li><strong>CI/CD:</strong> Linux servers, Jenkins for CI/CD pipelines, make/cmake for builds, and bash for scripting</li>
      <li><strong>Additional:</strong> I'd be happy to discuss my experience in jQuery, CSS, SQLite, MySQL, Nginx & Apache, bash, git, RESTful APIs, mDNS, and more.
      </li>
    </ul>
  </div>
</div>
<hr>
<div id="experience" class="row">
  <div class="col-md-3">
    <h3> Experience </h3>
  </div>
  <div class="col-md-9 content">
    <h4> Big Ass Fans
      <p>
        iOS Developer and Firmware Developer <span class="date">(2015-current)</span>
      </p>
    </h4>
    <ul>
      <li><strong>Role Overview</strong> - At Big Ass Fans, my responsibilities have shifted with the demands of the business. I was hired as an iOS developer working in Objective-C within the Controls group, but my responsibilities quickly came to include representing the company in the Thread Group, helping to define new hardware projects, leading a team as Product Owner, developing firmware in C/C++, and developing new applications in Swift.</li>
      <div class="page-break"></div>
      <li><strong>Notable projects</strong>
        <ul>
          <li><a href="https://apps.apple.com/us/app/haiku-by-baf/id902021647">Haiku by BAF</a> - I worked with another developer to add new features to this iOS application which controls all of BAF's residential products: fans, lights, wall controls. Features included: grouping, smart thermostat integration, and Apple HomeKit.</li>
          <li><a href="https://www.threadgroup.org">Thread Group</a> - I represented the interests of the company as the vice-chair of the Commercial Working Group, which was responsible for generating the 1.2 Thread Networking Specification's Commercial Extensions. Specifically, I helped write a proposal to support IP-based, secure commissioning and decommissionsing of Thread devices. Later, I represented BAF on the Thread Group Board of Directors.</li>
          <li><strong>BASNet</strong> - This was a suite of 5 hardware devices that would allow BAF to do wireless retrofits in the commercial space. The devices consisted of fans, lights, and wall switches that communicated over a Thread mesh network. I helped define the feature set, design the communications API, and build the iOS application.</li>
          <li><a href="https://www.bigassfans.com/docs/bafcon/cutsheet-bafcon.pdf">BAFCon</a> - BAFCon is a touchscreen controller for BAF's industrial fans. I helped define the product features, and was one of the primary developers on a team of four. I was responsible for selecting a UI framework, implementing major features in our embedded stack, architecting our device model, and defining a Bluetooth API to support OTA firmware updates. This product was so well-liked by management that is was fast-tracked and attached to all sales of BAF's premium products.</li>
          <li><a href="https://apps.apple.com/us/app/bafcon-updates/id1403542146">BAFCon Updates</a> - This is the iOS application responsible for updating BAFCon firmware over Bluetooth. I was the sole developer, and completed the project in 2 months. It supports downloading firmware from our servers, connecting over Bluetooth to BAFCons, and updating their firmware. It can support multiple, independent connections and updates, while giving the user valuable feedback during the process.</li>
          <li><a href="https://apps.apple.com/us/app/i6-by-baf/id1472272574">i6 by BAF</a> - BAF launched a new residential fan, and I worked with another developer to almost completely refactor the Haiku by BAF codebase. This effort is essentially a new platform for all next generation BAF residential products. I was responsible for updating our CoreData model, implementing our protobuf API, handling all startup tasks, implementing our account login, and the entire device on-boarding process over Bluetooth, amongst others.</li>
          <li><strong>Jenkins CI/CD build pipleine</strong> - Before I was at BAF, all iOS builds were done on developer computers. I built an automated pipeline on our shared Jenkins infrastructure to build all Pull Requests in Github, run all unit tests, report any builld or test failures to Slack and Github, upload build artifacts for successful, tagged builds to App Store Connect, release new builds to TestFlight, upload de-symbolication files to Fabric for crash-reporting
            </ul>
          </li>
        </ul>
      </li>
      <li><strong>Skills Used</strong> - Objective-C, Swift, C, C++, FreeRTOS, Networking Protocol design, API design, Agile/Scrum</li>
    </ul>
        
    <h4> Circumference, LTD
      <p>
        iOS Developer and Backend Web Developer <span class="date">(2015)</span>
      </p>
    </h4>
    <ul>
      <li><strong>Role Overview</strong> - Circumference is a small, lean start-up with multiple iOS products and services. As their first full-time engineer, I was brought on to take over development of their primary product, <a href="http://www.getverses.com">Verses</a>. I worked closely with the CEO and lead product designer to plan and design new features, roadmap feature-sets and releases, and implement all new features.</li>
      <li><strong>Notable projects</strong>
        <ul>
          <li><a href="https://apps.apple.com/us/app/verses-bible-memory/id939461663">Verses</a> - Created an Apple Watch app, implemented StoreKit to convert revenue model to in-app purchases, integrated with Twitter and Facebook for sharing content.</li>
          <li>Designed and built a web platform for content creation and management, integrating with Parse and Firebase cloud backends.</li>
        </ul>
      </li>
      <li><strong>Skills Used</strong> - Objective-C, PHP, git, Javascript, Laravel, jQuery, CSS, Composer, RESTful APIs, Agile/Scrum</li>
    </ul>

    <h4> eLink Design
      <p>
        Backend PHP Developer and iOS Developer <span class="date">(2014-2015)</span>
      </p>
    </h4>
    <ul>
      <li><strong>Role Overview</strong> - I was part of a small team that was responsible for everything from ecommerce sites; smaller, informational sites; large-scale international web applications; and enterprise mobile applications and intranets. Depending on the project, my role included managing a small team, being the sole developer, or work efficiently as part of a larger team.</li>
      <li><strong>Notable projects</strong>
        <ul>
          <li>Introduced several best-practices into the developer workflow: version control (git, and git-flow for branching), library versioning and dependency management (both through Cocoapods and Composer), and the use of local, development, and production environments.</li>
          <li><a href="https://apps.apple.com/us/app/bluegrass-staking/id872589656">Bluegrass Staking</a> - Created an iOS application that wrapped an existing web application to allow horse owners to enter their horses in races, view performance reports, and facilitating payments. It also allowed users to be notified of race lineup changes and results.</li>
          <li><a href="https://obckitchen.com">OBC Kitchen</a> - Created a custom menu iOS app deployed on iPads to each table, with management backend. Allowed for management to update the menu, pair drinks with entrees, and update pictures.</li>
        </ul>
      </li>
      <li><strong>Skills Used</strong> - PHP, Objective-C, LAMP, git, Symfony 2, Laravel, Wordpress, Javascript, jQuery, CSS, Composer, SOAP & RESTful APIs, HTML, CSS, Agile/Scrum</li>
    </ul>

    <h4> Software Development Consulting
      <p>
        Freelance <span class="date">(2010-2013)</span>
      </p>
    </h4>
    <ul>
      <li><strong>Role Overview</strong> - Part-time freelancer primarly doing client work in iOS and Ruby on Rails. Worked with a designer and front end developer to meet clients expectations and milestones.</li>
      <li><strong>Notable projects</strong>
        <ul>
          <li>Built a financial services web application that allowed financial advisors to track their performance for individual clients and portfolios.</li>
          <li>Built an iOS app for a client's internal use that allowed handwritten notes on PDFs.</li>
        </ul>
      </li>
      <li><strong>Skills Used</strong> - Objective-C, ruby, Rails, git, HTML</li>
    </ul>
  </div>
</div>
<div id="footer" class="footer">
  <a href="http://www.oflannabhra.com">Ben Flannery</a> -- <a href="mailto:ben.flannery@gmail.com">ben.flannery@gmail.com</a> -- (859) 338-3460
</div>