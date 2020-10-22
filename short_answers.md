# Short Answer Questions

Rahadian Pratama Irman
A01244754
midterm for 1620 October 2020
BCIT

# 1. Explain what Git and GitHub are. How are they different? 

Git is a system, which can track the version and changes within a source code and is intended for use in coordinated work between multiple programmers.

Github is a repository hosting service that works with managing git.

They are different in the way that they are complementary as github hosts repositories that are made using git. So github essentially helps managing the projects made in git.

# 2. What is a 'Branch' in Git? How could you create a new branch and what would you commonly use a branch for? 

A branch shows all the different changes within a project. So, when a change is made, a new branch is automatically made to represent that change. You could also make a new branch by doing "$ git branch <new-branch-name>" on git bash or do "$ git branch <new-branch-name><base-branch-name>" if you're adding to a new branch.

# 3. What is the http status code get when a resource is not found? What category of status code does this belong to (other status codes that start with the same number)? Does this status code indicate if the representation is permanent?

Resource not found has the 404 status code and is part of the 4xx(400-405) client error group. This status code does not indicate if the resource can/cannot be found permanently.

# 4. What is not correct about styling of the given h2 element in the code below? Which color will the h2 be and why?

The styling of the h2 element on the head is wrong because the "school" style will overide the h2 style in the header. Furthermore, the inline css style for h2 will override both of them, making the end resulting color of h2, red.

# 5. List and briefly describe the parts of a URL

    1. There is the protocol: hypertext transfer protocol (https)

    2. Domain name identifies which server is being requested

    3. Port is used to access web resources

    4. Path is the path to a particular resource on the web

    5. Parameters are a list of value pairs separated with a & symbol

    6. Anchors is a sort of bookmark to a another part of the resource for the browser to locate

# 6. What is an http header? Provide examples of three http header fields and briefly describe what each does

Headers let the client and the server pass information with either a http response or request. 

The request header is what the application sends via http to the server, requesting to execute an action.

If there is a server in the address from the request header, then the server will return a response via the response header.

The accept header will show the type of content the client can understand.

# 7. Describe the CSS box model? From inside to outside what are the different parts of the box model?

It describes the box that surrounds all html elements. From inside to outside they go on the order of content, padding, border and margin.

# 8. Briefly describe the 4 CSS Combinator selectors that we looked at in class. Provide an example of each.

There are descendant combinators, which selects instances of the second element that appear in the first element. Ex: ".short p{}" looks for paragraphs in the class "short".

Child combinator is placed between between 2 elements that are directly parent and child. ex: short > p refers to paragraphs, which are direct children to the short class.

Adjacent sibling combinators are used to select elements that appear one after the other. In "short + p" refers to p elements that come after the short class.

General sibling combinators select siblings even when they are not adjacent. In "short ~ p" this refers to p elements that appear anywhere after the short class.

# 9. Will these two paragraphs appear on two separate lines? Why?

Yes, because the p element always signifies a new line.

# 10. Identify and explain two of the errors that exist in the code snippet below.

The fact that style is inside </a> means that it will be printed on the webpage, alongside "bcit site". Also you are not able to use title element as a style.