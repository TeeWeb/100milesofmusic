# 100milesofmusic
Repository for the blog

--- Current Working Theme: TeeWeb ---
The main stylesheet being used can be found in wp-content > themes > TeeWeb > "style.css". The TeeWeb theme was cloned from the default "twentyseventeen" wordpress theme. In the TeeWeb theme directory, you'll also find an "_images" directory and "footer.php" file.

--- Editing Theme's HTML Elements ---
Being that wordpress uses php to assemble html elements, please follow this process when attempting to edit the html elements in the site:

1) Find the respective element in the current working theme directory (ie. if you want to edit the footer element, navigate to wp-content > themes > TeeWeb > footer.php). This is the file that you will EDIT. If the desired element is not found in the current theme directory, that just means that it has not been changed from the default "twentyseventeen" theme. To do this, proceed to Step 2...
2) Navigate to wp-content > themes > twentyseventeen and find the respective php file for the element you want to edit (ie. to edit the header element, find "header.php" in the twentyseventeen theme directory)
3) COPY the php file and paste into the current theme directory (ie. TeeWeb directory)
4) Now you can EDIT the php file and the site will automatically prioritize the file located in "TeeWeb" theme over the default "twentyseventeen" theme