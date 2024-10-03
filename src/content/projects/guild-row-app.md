---
title: 'Guild Row Member Directory'
description: 'A Next.js single-page web application for connecting members within a co-working space.'
pubDate: 'Sept 08 2024'
heroImage: '/gr-member-app.jpg'
---

I was first approached by the directors of Guild Row in 2023 while I was working there as a barista. They had known at the time that I was studying computer science and had the great idea of creating a web app that displayed different skills and hobbies the members at the space shared. I instantly fell in love with the idea as it was a great way to materialize my favorite part of the club: exposure to shared interests through real-life connections.

The idea began when the directors sent out a Google Form that members would fill out with questions such as occupation, hobbies/interests, skills they are open to sharing, and consent to be added to the member directory. From here, I took over the web development and UI/UX design. I decided to use the Next.js framework because I wanted the site to be a single page application for user simplicity. The design I ended up using focused on standard web design principles while maintaining the brand motifs that Guild Row had already established. The design process took about a week and a half as I met with the director of marketing to make sure the application aligned with the club's design patterns. 

To begin working on the app, I used the Google Sheets API to make RESTful calls to the form response sheet and utilized the React Redux library to hydrate the webpage with the data as soon as it is loaded. The web page is entirely server-side rendered, allowing for instantaneous member searching and filtering which greatly increases the user experience. This made it easy for me to implement the searchbar and filter components as well because only one READ request is needed to be made. The web development process took about 3 weeks to finalize with bi-weekly meetings to ensure all user functions were being made to the directors intentions.

The directory was hosted on Vercel, allowing me to easily make updates if needed. For member privacy concerns, the site is password protected.


