---
title: "SafeBites"
excerpt: "iOS App to find Allergens in any language<br/><img src='/images/safeBites.png'>"
collection: portfolio
tools: "(Swift, VisionKit, iOS, SwiftUI)"
---

Demo Video: https://www.youtube.com/watch?v=evU1T4tzB8Q

Github Repo: https://github.com/Nsilswal/Safe-Bites

[![Demo Video](https://img.youtube.com/vi/evU1T4tzB8Q/0.jpg)](https://www.youtube.com/watch?v=evU1T4tzB8Q)

SafeBites Won the Accessibility Track Award at the HackDuke Hackathon in 2023

## Inspirations

I have struggled with food allergies my entire life, with some of my scariest memories being the aftermath of accidentally eating an almond or having a piece of shrimp on my plate. This trauma inhibits me from trying new foods. I, oftentimes, find myself in situations where friends offer me snacks, and I have to awkwardly say no since the ingredients will be in a language I can’t read. I know I have company, as 220 million people deal with food allergies, globally, and 40% of the world’s population is monolingual. Safe Bites can play a significant role in enhancing patient safety for individuals with known allergies and intolerances. By recognizing and scanning ingredient lists in any language, and cross-checking with the users’ sensitivities, Safe Bites can help prevent accidental exposure and allergic reactions, which can range from mild discomfort to life-threatening situations.

## Learnings

We started off this weekend learning mind blowing and saddening information from Justin Klein, which prompted us to think more about enhancing the lives, through health, for everyone. Early on in this process, we also spoke with other medical experts to identify common problems and receive feedback on our ideas. A takeaway was that there is a lot of work to be done for enhancing health resources and technology, while establishing and maintaining equity. For our project, specifically, we eliminated biases by enabling users to input their specific allergens that might be more rare, personalizing the experience. Learning about the significant monolingual population, we also made an effort to build a product that could detect languages rather than relying on users to have that advanced knowledge. Technically, we became increasingly familiar with Swift, and utilized VisionKit & APIs described below for the first time.

## Building

We built the project by defining our goals and breaking them down into subcomponents, separated by physical screens and technologies used. We implemented a language picker on the Home page so that users can choose the language of the text they view. On the Allergens tab, we created a checklist with some pre-filled defaults, saving users’ time and helping them think through all possible intolerances. This preset list tackles the most common, 90%, of all food allergens. To personalize the experience, users can add their own items they want to be on the lookout for. For the Scanner tab, we utilized Apple’s VisionKit to scan text, Google Translate’s API, and wrote many of our own views, structs, and functions in Swift to reach this fully functional product. We started off by testing bits and pieces using fabricated ingredients lists, then tested on real-life food objects, constantly iterating.

## Challenges

While working on this project has been extremely rewarding, there were definitely several challenges that we faced. We both had minimal exposure to Swift, so there was a major learning curve. However, this reinforced our love for learning by doing. We also had instances where merging code was tedious, as XCode and Git do not mesh as well as we were anticipating. We had limited access to real-life testing, as almost all food products we identified on Duke’s campus had an English ingredient list, making it difficult for us to see if the translation component was working smoothly. We ended up making a few trips to different grocery stores to pick items that ended up being great test products.
