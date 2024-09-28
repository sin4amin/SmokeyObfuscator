First off shout-out to @Gerbsec for this application, as it's a great base for someone like me to go from and not just a base a very-decent and neatly written way to go about this, as i've not really seen it done this way often but I like it lot and plan to work off this for quite some time. I will be closig up a private project for a priavte customer that was taking up a great deal of my time, and I'll be back to way more free-time & more time for me to work on this, and I look forward to it. Although I have not had any chance to speak to @gerbsec or any for that matter about possible getting a nice group together and really making this into something great as I think it has potential. I added a 'RenameClasses.cs' into the Protections list along-side the other files from original created: '@gerbsec'. I intend on updating the thread / repository in just a few hours -- or by the end of the Night > Currently 3:55PM EST 09/28/2024 as of this writing for reference. If you are interested in working along-side on this project perhaps we can start a telegram/signal/whats-app/discord type group if it makes any noise so to say. I'll attach 2 pictures, 1 of the 'RenameClasses.cs' I added to and a picture with the Symbols/Chars for renaming with all different sets/what worked the best etc.. might make a Form with options etc. like a .NET Reactor type look (But new and better) but with the appropriate options for building/editing the file or excluding due to certain .exe obfuscations when crypted being compatible etc..

RenameClasses.cs with Testing out of different Symbols/Chars. for All renaming.
Seems to work so far with current set in-place. Need to keep testing more later tonight:
![alt text](https://i.ibb.co/CvfDz2C/Screenshot-2024-09-28-160358.png)

What RenameClasses.cs Does to class names:
![alt text](https://i.ibb.co/Xk4wy5h/Screenshot-2024-09-28-154559.png)






# SmokeyObfuscator - Universal .NET C# Obfuscator for Windows

SmokeyObfuscator is a powerful tool designed to obfuscate .NET C# assemblies, enhancing security for your applications by making it difficult for reverse engineers to understand and tamper with your code.

## Features

- **Universal Compatibility**: Works seamlessly with .NET C# assemblies targeting various versions of the .NET Framework.
- **Advanced Obfuscation Techniques**: Employs sophisticated obfuscation techniques to scramble your code, making it extremely challenging to reverse engineer.
- **Enhanced Security**: Protects your intellectual property and sensitive algorithms from being easily understood or stolen.
- **Command-Line Interface**: Provides a command-line interface for easy integration into build processes and automation scripts.
- **Customization Options**: Offers a range of customization options to tailor the obfuscation process to your specific needs.

## Installation

1. Download the latest release of SmokeyObfuscator from the [Releases](https://github.com/gerbsec/SmokeyObfuscator/releases) page.
2. Extract the downloaded ZIP file to a directory on your Windows machine.

## Usage

SmokeyObfuscator is operated entirely from the command line, providing a straightforward way to obfuscate assemblies as part of automated scripts or manual operations.

### Basic Commands

- **Obfuscate a Directory**:
  ```
  SmokeyObfuscator.exe -d <path-to-directory>
  ```
  This command will obfuscate all compatible files within the specified directory.

- **Obfuscate a Single File**:
  ```
  SmokeyObfuscator.exe -f <path-to-file>
  ```
  Use this command to obfuscate a specific file.

- **Help**:
  ```
  SmokeyObfuscator.exe -h
  ```
  Displays usage information and help about the command-line arguments.

### Example

To obfuscate all files in a directory called `bin/Release`, navigate to the directory where `SmokeyObfuscator.exe` is located and run:
```
SmokeyObfuscator.exe -d "C:\Path\To\Your\Project\bin\Release"
```

To obfuscate a single assembly named `MyApp.exe` in the directory `bin/Release`, run:
```
SmokeyObfuscator.exe -f "C:\Path\To\Your\Project\bin\Release\MyApp.exe"
```

## Support

For any issues, bugs, or feature requests, please [open an issue](https://github.com/gerbsec/SmokeyObfuscator/issues) on GitHub. Your feedback helps make SmokeyObfuscator better for everyone.
