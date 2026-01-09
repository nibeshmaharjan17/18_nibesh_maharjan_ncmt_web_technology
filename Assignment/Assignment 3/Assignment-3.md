# Web Technology  
## Assignment 

**Student Name:** Nibesh Maharjan
**Roll/ID No:** 18
**Program:** BIT  
**Date:** January 9, 2025

##  CHAPTER 3: WEBSITE STRUCTURE DESIGN

## Group A:

### 1. Define Information Architecture (IA).

Answer: Information Architecture (IA) is the practice of organizing, structuring, and labeling content in an effective and sustainable way. Its goal is to help users find information and complete tasks by making the navigation and categorization of the site intuitive.


### 2. What is a ”Wireframe”?

Answer: A wireframe is a basic outline of a webpage. It shows the placement of content and functions like buttons and text, but does not include design elements. It serves as a visual structure for the website.


### 3. Explain the concept of ”Cognitive Friction” in web design.

Answer: Cognitive friction occurs when a user is faced with an interface that is unintuitive or behaves differently than they expect. It forces the user to stop and think about how to use the site, leading to frustration and a higher bounce rate.

### 4. Why should URL slugs use hyphens instead of underscores?

Answer: Search engines, such as Google, regard hyphens as separators between words. This helps the search engine's ability to crawl and recognize keywords in a URL. In contrast, underscores tend to be viewed as part of a word. For example, 'web_design' would be seen as 'webdesign,' and this can negatively affect search engine optimization.


## Group B: 


### 5. Compare and contrast Hierarchical (Tree) structure and Linear (Sequential) structure. Give an example of when to use each.

Answer: The structural model of a website, which dictates information organization and user navigation, typically follows either a hierarchical or a linear structure. Selecting the right model is crucial for meeting user expectations.

**Main Differences**

*   **Navigation:** Tree structures branch out, while linear paths proceed directly.
*   **User Control:** Tree structures let users explore more freely, but linear paths limit freedom.
*   **Amount of Content:** Tree structures are good for large content, while linear structures are better for step-by-step items.
*   **Ideal Use:** Use a tree structure for exploring and a linear structure for finishing tasks.

Website structures often follow one of two main models: hierarchical or linear.

1.  **Hierarchical (Tree) Structure:**
 Most sites use a tree structure. The homepage acts as the starting point, branching out to broader categories and then to more specific subcategories.

 *   Users can explore sections that interest them. This works well for sites with a lot of content that needs topic-based organization.
 *  Example: University websites or online stores commonly use this structure.

2.  **Linear (Sequential) Structure:**
 This structure guides users along a specific path, usually with forward and backward navigation.

 *  This makes sure users see key info or complete steps in the right order. By limiting choices, it can also reduce confusion.
 *   Example: Online checkout processes or tests often use this model.


### 6. Explain the ”Three-Click Rule” and its significance in User Experience (UX) design.

Answer: The Three-Click Rule is a popular web design concept suggesting users should locate info on a website within three clicks from the homepage. Going over this limit could frustrate users, causing them to leave.

Its significance in  user experience:

* Intuitive Navigation: Recent research suggests the three-click rule isn't a strict standard. Users will click more if they feel they are heading in the right direction.      The rule is still valuable, encouraging designers to create logical and clear site structures. Content should flow from broad to specific topics naturally.

* Reduced Cognitive Load: The core idea is to minimize user effort. Fewer clicks usually means simpler navigation and less cluttered layouts, making the site easier to         explore and comprehend.

* Speed and Efficiency: For e-commerce sites, speed is crucial. Fewer steps to purchase an item or locate a product can increase sales.

* User Retention: Online users have short attention spans. If finding what they need is difficult or requires too much effort, they will leave. This rule reminds us to keep    important info accessible, not buried deep within the site.


### 7. ”Plan before you do.” Explain how tools like Card Sorting and Flowcharts help in planning a website’s structure.

Answer: Website structure planning benefits from employing card sorting and flowcharts, which helps with planning before implementation.

1. Card Sorting: User-Focused Content Arrangement
Card sorting is a user research method used in designing a site's information architecture (IA).

How it helps: Designers write topics on cards and have users group them into categories. This shows how users think about the information.
Result: The website navigation matches user thinking, preventing confusing structure and helping users find what they need.

2. Flowcharts: Mapping the User's Path
A flowchart is a visual diagram showing the steps a user takes to achieve an action or move through the site.

How it helps: Flowcharts link pages, showing how the homepage, sub-pages, and actions relate. This identifies dead ends or difficult paths before coding.
It acts as a plan for the site's logic. By visualizing the flow, designers can spot missing pages or repeated steps, which ensures a smooth user experience.

In summary, card sorting ensures correct content grouping, and flowcharts confirm that navigation works. These tools save time and money by preventing major structure mistakes.


## Group C:


### 8. You are designing a website for a University. It has hundreds of pages (Admissions, Departments, Alumni, News). Which structural model would you choose? Draw a rough diagram and justify your choice.

Answer: For a university website with hundreds of pages and diverse user groups (students, faculty, alumni, applicants), the best choice is a Hierarchical Structure, often referred to as a "Tree" structure. Specifically, a Broad Hierarchy is preferred over a deep one to keep content accessible.

* Logical Organization of Complex Data :
University websites are content-heavy. A hierarchical structure allows you to break down massive amounts of information into manageable categories. Users intuitively understand that general categories (like "Academics") will contain specific sub-categories (like "Departments" or "Library"). This matches the mental model most people have of a large organization.

* Scalability (2 Marks):
  Universities are dynamic; new research centers open, and new courses are added. A hierarchical tree is highly scalable. You can easily add a new branch under "Departments" without disrupting the rest of the website's architecture. It grows neatly without becoming chaotic.

* Clear Navigation Paths for Diverse Audiences :
  A university serves very different users.
 A prospective student needs "Admissions."
 A current student needs "Library" or "Canvas/Portal."
 An older donor needs "Alumni."
 The hierarchical model allows the homepage to act as a central hub (or switchboard) that quickly routes these different personas down their specific "branches" so they don't get lost in irrelevant content.


### 9. A user visits a website but leaves within 10 seconds because they cannot find the navigationmenu, which is hidden behind a small icon on a desktop screen. Analyze this design failure using the ”KISS” (Keep It Simple) principle.

Answer: The KISS principle, which is short for Keep It Simple, Stupid, suggests that simplicity should be a key goal in design. A design that goes against this principle often has problems with how easy it is to use.

In the case described, the design wasn't successful as it seemed to value a minimalist look more than making it obvious how to interact with the design. Affordance, in design terms, refers to the visual cues that tell a user what they can do with an object or element. For example, a button should look like it can be pressed or clicked.

The mistake here was hiding the main navigation behind a small icon, especially on a desktop screen where there's enough space for a more visible menu. This creates what's called Cognitive Friction, which means users have to spend extra mental effort to figure out how to use the site. It makes the experience less smooth and intuitive.

To fix this, the design should stick to the KISS principle. The navigation should be clearly visible, probably in a bar at the top or side of the screen. A simple design focuses on making the most important actions obvious to the user. Hiding essential functions to make a page look clean actually makes it harder to use, which defeats the purpose of good design. The aim is to make the user experience as intuitive and effortless as possible by prioritizing clear and obvious navigation.


### 10. An e-commerce website has a URL structure like www.shop.com/prod?id=55&cat=9. Explain why this is bad for both users and Search Engines (SEO), and propose a better structure using Page Slugs.

Answer: It is important to think about URL structure for e-commerce sites in relation to search engine ranking.

**Problems with Dynamic URLs**

Consider this: `www.shop.com/prod?id=55&amp;cat=9`. This kind of URL, often called a dynamic URL, presents a number of problems. First, it is not user-friendly. It's hard for people to understand or remember since it is just a string of characters. Second, these URLs are not good for search engine ranking. They usually lack important keywords that assist search engines in understanding the page's topic. Also, search engines often find it harder to process dynamic URLs with query strings than URLs with a more stable structure.

**A Better Approach: Descriptive Page Slugs**

A better method is to use a descriptive page slug structure.

For instance, instead of the dynamic URL above, use something like this: `www.shop.com/electronics/noise-cancelling-headphones`.

**Good things about the suggested URL:**

This type of URL gives benefits to both users and search engines:

*   **User-Friendly:** It tells users exactly what they can find on the page. Someone can guess the page's content just from the URL.
*   **Better search engine ranking:** It contains important keywords (electronics, noise-canceling headphones) that assist search engines to more easily see the page's focus. This can help the page get a higher rank in search results for those terms.

