# Tetris-
Prototype of the popular game tertris in C#, using tetromino figures !

# Functions
- Classic game mode
- Keyboard control

# Dependencies
- .NET Framework 
- WPF
- GNU make  if you use linux 
- Visual Studio 2022 or another IDE for C# ( it is strongly recommended to use Visual studio )

# How to play?
Clone the repository:
    ```
  https://github.com/db-NeverRmore/Tetris-.git
    ```
    
2. Open the project in Visual Studio or another IDE for C#.
3. Build and run the project.
4. Use the arrows on your keyboard to play 

# Attribution
If you want to contribute to your project you can submit a co-development request !

# If I'm using linux

Running WPF on Linux can be challenging because WPF is designed specifically for the Windows operating system.
However, it can still be done, but it will be far from perfect.

Actions that will help you launch this project 
# Use of Avalonia 
```
sudo apt-get update
sudo apt-get install -y dotnet-sdk-7.0
```
```
dotnet new avalonia.app -o MyAvaloniaApp
cd MyAvaloniaApp
dotnet run
```
# With wine
```
sudo apt-get install wine
wine ur_project.exe
```
# Mono-develope 
```
sudo apt-get update
sudo apt-get install mono-complete
```
Then prepare your Mono-develope IDE by installing the compiler if required.
