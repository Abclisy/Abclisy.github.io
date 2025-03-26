_config.yml

    - Add Avatar: Add a .png file after the "avatar" field. This will only work if you change the "url:" 
                  in the "#Basic Site Settings" to your own GitHub link.

    - Add GitHub Link: Update the "github" field with your GitHub username (just the username, no link needed).

    - Cancel Title: The title can be found in the "#Basic Site Settings" under the "title" field. 
                    I didn't remove it because it helps people easily navigate back to your homepage.

_data/navigation.yml

    - Remove Unwanted Navigation: You can delete any navigation items you don't want here. 
                                  You can also reorder the navigation or add new items.

_includes/footer.html

    - Remove "FEED": I have only commented out the "FEED" code instead of deleting it, 
                     so you can uncomment it whenever you need to.

_pages/cv.md

    - Add CV.pdf to Navigation: First, choose /cv/ instead of /cv-json/ in the "_data/navigation.yml". 
                                Then, add the following code to the cv.md:

                                <embed src="{{ site.baseurl }}/files/CV_ShengyuLi.pdf" width="900" height="1000" type='application/pdf'>

                                I have also added a "Download CV as PDF" button at both the top and bottom of your CV.
