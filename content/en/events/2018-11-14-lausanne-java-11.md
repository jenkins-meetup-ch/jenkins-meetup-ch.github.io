---
title: "JUG Lausanne: From Java 8 to Java 11 in Jenkins"
date: 2018-11-14T18:30:00+01:00
location: "Lausanne"
venue: "OCTO Technology"
description: "Oleg Nenashev shared the Jenkins project's experience of adding Java 11 support."
meetup_url: "https://www.meetup.com/swiss-jenkins-area-meetup/events/255914568/"
cover_image: "images/events/474166501.png"
cover_alt: "Jenkins Meetup Switzerland logo with the Jenkins mascot and Swiss cross"
---

Jenkins, one of the leading open-source automation servers, has not been supporting Java 9 and above since its official release. Over the last year Jenkins contributors were working towards the support of Java 11 (Jenkins JEP-211). Jenkins has a huge and sometimes legacy Java/Groovy/native codebase, includes DSL engines, and depends on many upstream libraries and modules (including ones deleted from Java 11). It was a thorny way, but Java 11 support is almost ready to be released.

In this talk I would like to share our experiences and talk about potential obstacles others may hit while implementing Java 11 support in their projects. What issues have we hit while implementing support of Java 11 in the core? Are modules and deprecations that tricky for a web application (spoiler: no)? How have we enabled building and testing with OpenJDK 11 in our Maven-based pipelines? And how have we retained Java 8 compatibility after all these changes?

The presentation will be in English.

### Speaker

Affiliation: Jenkins core maintainer, Principal Engineer at CloudBees

R&D and Automation engineer with Hardware/Embedded background. Oleg started contributing to Jenkins in 2012, and became a core maintainer in 2015. He focuses on Jenkins architecture and platform reliability. Oleg holds the Jenkins Ambassador title and organizes community events including Swiss Jenkins Meetup and Google Summer of Code. He also leads the Jenkins Platform SIG and leads the Java 11 compatibility project there. At CloudBees he is focused on making Jenkins cloud-native. Oleg also has a PhD degree in Hardware Engineering and contributes to the LibreCores project.

### Links

- Jenkins website: [https://jenkins.io/](https://jenkins.io/)
- Jenkins JEP-211 “Java 11 support in Jenkins”: [https://github.com/jenkinsci/jep/tree/master/jep/211](https://github.com/jenkinsci/jep/tree/master/jep/211)
- Jenkins Platform SIG: [https://jenkins.io/sigs/platform/](https://jenkins.io/sigs/platform/)

The [JUG Lausanne listing](https://www.meetup.com/JUGL-the-Java-User-Group-of-Lausanne/events/255766372/)
was the registration page for the event.

### Recording

{{< youtube 18wVyYaZvTw >}}

[Watch the talk on YouTube](https://www.youtube.com/watch?v=18wVyYaZvTw),
published by JUG Lausanne.

### Slides

[View the presentation slides on Speaker Deck](https://speakerdeck.com/onenashev/leap-from-java-8-to-java-11-in-jenkins-our-war-story).
