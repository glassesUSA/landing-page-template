## Usage
Paste this command into the terminal inside the folder where you want the files to be copied to and follow the instructions.

```bash
echo "Please enter the directory where you want the project to be cloned to (Use . to use the current directory):" && read x && git clone https://github.com/glassesUSA/landing-page-template $x  && rm -rf $x/.git && rm -f $x/README.md
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
