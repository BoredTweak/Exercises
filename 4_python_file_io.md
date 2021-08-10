# Python File IO

Exercises intended to introduce interacting with various types of files in Python. For each task create a new file and store it in a GitHub repository.

## Prep

- [Install Python](https://www.python.org/downloads/)
- [Install Visual Studio Code](https://code.visualstudio.com/download)

- Create a Text File named `sample.txt` and store the following text in it
```sample.txt
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
```

- Create a JSON file named `sample.json` and store the following text in it
```json
{
    "name": "Joe", 
    "age": 2,
    "colors": [
        "red",
        "orange",
        "yellow"
    ]
}
```

- Save [this image](https://user-images.githubusercontent.com/13189530/128786089-3dcd76f6-db6a-4218-838d-22336e821f71.png) as `sample.png` in the same directory as `sample.txt`.


## Exercises

- Read all lines from `sample.txt` and output them to console.
- Read the first line from `sample.txt` and output it to console.
- Read `sample.txt` and output to console only lines that don't start with `Ut`.
- Read user input and overwrite `sample.txt` with the input.
- Read user input and append it to the end of `sample.txt`.
- Read `sample.json` and print the `name` property to console output.
- Read `sample.json`, add a new property `fruit` with the value `banana` to the json dictionary, then save it as `sampleFruit.json`
- Read `sample.json` and iteratively print each property in the JSON file.
- Read `sample.json` and iteratively print each value in the `colors` property.
- Read `sample.png` and save a copy as `sample2.png`.
- Create an image `sampleTextToImage.png` which contains the text `Hello World of bunnies and stuff`.
