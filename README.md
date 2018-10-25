# GoogleImageDownloader

This is the code for [this video]() by Ritesh on [YouTube](https://www.youtube.com/RiteshKumarMaurya).

**A Python program for downloading images from a Google Search.**

While Making KNOIT-An Android APP for Object Detection and Classification-[Download Here](https://play.google.com/store/apps/details?id=com.knoit.tflitecamerademo), it was a very time taking process for downloading images manually which were required for the training process in a CNN(Convolutional Neural Network). So I came up with a program called imagedownloader.py which is purely built for downloading the images from a Google Search.

# SETUP
The program uses many inbuilt modules and only one third party module-BeautifulSoup.
So, you need to install it before using the program. Install it by:

    pip install BeautifulSoup4
    
Now you are good to go.

# RUN

Open your Command Prompt or Terminal and change directory to the same folder where you have saved the program.
Now create a new Folder or choose an existing one where you want to save the downloaded images.
Finally, type the following in your CMD or Terminal:

    python image_downloader.py -n 100 -s "Red Roses" -d "G:\__Main__\Pictures"
    
Here, change the following as per your needs:
**-n:**
    Number of Images to be downloaded.
   
**-s:**
    Search Query.

**-d:**
    Directory where to save the images.
    
That's it guys. Please do **STAR** the Repository and be my follower here on GitHub as well as a Subscriber on YouTube.
