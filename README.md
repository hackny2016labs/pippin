# Pippin
A responsive CSS framework built in Sass

### Usage 

In the `dist/` folder, download `pippin.min.css` and `pippin.min.js`. Then, include them into your own project directory. Make sure to properly link both files in your html or jade files to apply Pippin's styling and functionality. 


### Developer Notes

#### Installation 

Clone this repository `git clone https://github.com/hackny2016labs/pippin.git`. Navigate to the cloned folder in your local directory and use `npm install` to install all the required dependencies, noted in `package.json`. 

#### Running

We use gulp as a task running tool. Run `gulp` to run the default script to watch all .scss and .js files.

Run `gulp build` in order to translate all source .scss and .js files to our minified production folder `dist/`. 

