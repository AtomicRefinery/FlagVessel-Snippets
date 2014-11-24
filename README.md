FlagVessel-Snippets
===================

A list of snippet code to resolve custom issues
--------------------------------------------------
a way to keep the logo from disappearing once the website is scrolled down

@media only screen and (min-width: 1000px){header.stick_with_left_right_menu.sticky .header_inner_left {display: inline-block;width: 9%;}header.stick_with_left_right_menu.sticky nav.main_menu.left_side, header.stick_with_left_right_menu.sticky nav.main_menu.right_side{width: 45%;}}

--------------------------------------------------

use Vertical split slider in a simple fullwidht page?
You can hide these buttons by adding the following code to your custom css field:

#multiscroll-nav{
display:none;
}


-----------------------------------------------

To change the font size and color of the team name, you can add the following code to your custom css field and modify the color value and font size value to suit your needs:

.q_team .q_team_title_holder h3.q_team_name {
color: #fff000;
font-size: 20px;
}
And to change the font size and color of the description text, you can use the following code:

.q_team .q_team_description_inner p {
color: #fff000;
font-size: 18px;
}



-----------------------------------------------

You can use the following code to set a top margin for your masonry blog list:

.page-template-blog-masonry-php .blog_holder {
margin-top: 50px;
}
Just paste this code into your custom css field and adjust the 50px value to suit your needs.

----------------------------------------------------


For those of you that use Ultimate Addons for VC there is a conflict with their heading element and the theme. With a sub-heading written one could not change the font or the color; stayed black. My friends in India at Ult. Addons said there were extra p tags in the content area. TO FIX THIS: add the following to the custom css in qode options:

.uvc-sub-heading * { font-family: inherit; font-weight: inherit; font-size: inherit; color: inherit; }

-----------------------------------------------------

You can use the following code to make sure all the buttons on your site have the same colors and act the same on hover. Just put this code into your custom css field and edit the color values to suit your needs:

.qbutton{
    color: #000 !important;
    background-color: #FFF !important;
}

.qbutton:hover{
    color: #FFF !important;
    background-color: #000 !important;}
    
    
    --------------------------------------------------
    
    
    Regarding your question, this could be done via some custom css. But then you would have to also disable the “view” and “zoom” buttons for your portfolio, so only the title and categories are visible on hover, since you can’t have the whole image clickable as a link and then have two other links inside it (they wouldn’t work). If you would like this, you can achieve it by placing the following code in your custom css field:

.projects_holder.hover_text article .feature_holder .feature_holder_icons {
display: none;
}

.projects_holder article span.text_holder {
pointer-events: none;
}


--------------------------------------------------
remove: About this project and category

.portfolio_single .info.portfolio_categories, .portfolio_single .portfolio_single_text_holder {
display: none;
}

.portfolio_single .two_columns_75_25>.column2{
float: right;
}









    
    
    
    
  
