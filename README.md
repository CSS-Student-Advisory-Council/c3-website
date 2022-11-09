## [Live site is up on netlify](cscareersuwb.netlify.app)




## Setup
### 1\. Clone this Repository

```
git clone https://github.com/CSS-Student-Advisory-Council/c3-website.git
```

### 2\. Navigate to the directory

```
cd c3-website
```

### 3\. Install dependencies

```
npm install
```

### 4\. Build the project to generate the first CSS

This step is only required the very first time.

```
npm run build
```

### 5\. Run Eleventy

```
npm run start
```

### Contributing 
This repository has a *src/* directory and a *_site/* directory. 

The *src/* directory contains our elements for the website. The *_site/* directory is the main directory for the website. 

For making changes to the text on the website, you can do it easily by modifying the markdown files in *src/posts/*.  After you make changes, run 
```npm run build``` 
to convert them into HTML.

For adding JavaScript to the website, its a little different. All scripts need to be somewhere in the *_site/* directory. 
This is because the website will use *_site/* as the root directory.



## Credits
This site is based off the Neat Starter created by Surjith S M ( [@surjithctly](https://surjithctly.in/) )

[ More Detailed Instructions on installation](https://blog.surjithctly.in/neat-stack-create-a-static-website-with-netlify-cms-eleventy-alpinejs-and-tailwindcss)
