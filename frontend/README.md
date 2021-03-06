# Readable frontend
This frontend requires the backend to work. Start the backend server first if you haven't already done so. To start the frontend. Type the following commands.
```
npm install
npm start
```
The application wil start up in the mainview.

## Mainview
The mainview can be seen in figure 1. 
 
![Figure 1](https://github.com/cbrands/reactnd-project-readable-starter/blob/master/frontend/figures/Figure_1.png "Figure 1")

1. The application runs at localhost port 3000.
2. The house and de title are links to the home screen.
3. Click on a category to select this category. 
4. Upvote and downvote buttons and the score.
5. Dropdown box with two options
	* Sort by date
	* Sort by score
6. Click on the post title to go to the detail view of that post
7. Shows the number of comments on a certain post
8. Button to edit the post
9. Button to delete the post

When a category is selected (in this example 'React') only the posts belonging to that category is shown as isdepicted in figure 2.

![Figure 2](https://github.com/cbrands/reactnd-project-readable-starter/blob/master/frontend/figures/Figure_2.png "Figure 2") 

1. The url shows the selected category.
2. A button "New post" appears.
3. Posts not belonging to the selected category are no longer visible.

## Post detail view
The postdetail view is depicted in figure 3.
![Figure 3](https://github.com/cbrands/reactnd-project-readable-starter/blob/master/frontend/figures/Figure_3.png "Figure 3")

1. Post-id is in the url
2. Post title, body, and author are shown
3. Edit and delete buttons + comment count
4. Upvote/downvote buttons for the post
5. Upvote/downvote buttons are present for each comment
6. Dropdown box with two options
	* Sort by date
	* Sort by score
7. New comment button
8. Edit and delete buttons

## Edit / new post
Figure 4 shows the edit/new post screen.
![Figure 4](https://github.com/cbrands/reactnd-project-readable-starter/blob/master/frontend/figures/Figure_4.png "Figure 4")

1. Url showing category, post id and the word "edit". For the new post screen the url is http://localhost:3000/${category}/new
2. Reads "Edit post" for the edit screen "New post" for the new post screen.
3. Input fields for Title, body, and author.
4. Cancel button.
5. Save button.

## Edit / new comment
Figure 5 shows the edit/new comment screen.

![Figure 5](https://github.com/cbrands/reactnd-project-readable-starter/blob/master/frontend/figures/figure_5.png "Figure 5")

1. Url showing the comment id. For the new comment screen the url reads http://localhost:3000/comments/new
2. Reads "Edit comment" for the edit screen "New comment" for the new comment screen.
3. Input fields for comment, and author.
4. Cancel button.
5. Save button.
