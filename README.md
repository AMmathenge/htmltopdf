# create the folder

 which will house your index.html and footer.html 


## write your code 

in simple html and css.

Try as much not to use flex and grid instead use table in css 



## Run the code 

To see the output from your code you could use vscode live server to run


# Install wkhtmltopdf


For linux

open terminal 

sudo apt-get update

sudo apt-get install -y wkhtmltopdf


## Before use check the version

 wkhtmltopdf --version


 # concat the index.html and footer.html to temp2


cat /path/to/your/index.html /path/to/your/footer.html > /path/to/your/temp2.html


# Conversion from  html to pdf

--enable-local-file-access does magic do not forget it


tawa9.pdf rename to the page of you liking

wkhtmltopdf --enable-local-file-access /path/to/your/temp2.html /path/to/your/tawa9.pdf
# htmltopdf
