1. Install the requirements for ruby and jekyll

2. Run ```jekyll serve``` to run in local server

3. By running the ```jekyll serve```, it will generate ```_site``` folder. The content of this folder needs to be uploaded in cloud server.


#### Important file/folder structure:
* ``perseo_speakers/_posts/`` contains all the information of the speakers in markdown files.

    Template for the markdown file: 
    ```
                ---
                title: Prof. ABC XYZ
                name: ABC-XYZ
                affiliation: University of CDE, KL
                subtitle: Academia
                layout: 2017_default
                modal-id: 1
                img:  ABC-XYZ.jpg
                thumbnail: ABC-XYZ.jpg
                alt: Picture of ABC-XYZ
                topic: QWERTY
                description: TBD
                ---
    ```
* ``perseo_teams/_posts/`` contains all the information of the organizing teams in markdown files.

* ``css/perseo_style/`` contains all the images for the websites including logos, speakers and team