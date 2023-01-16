# NumberToWordConverter

> This package was built to  help  C# developers do basic figure number to word conversion with ease and not having to do alot of work .

## Built With

- Languages: C#
- Frameworks: .NET Standard 2.0
- Technologies: Github and Visual Studio

## Code Base Repository

[Repo](https://github.com/Henrymenez/NumberCoverterToWord)

## Getting Started

  - To install our package using the .NET CLI, run: `dotnet add package numberToWordConverter-m88 --version 1.0.1`
  - Installation using Visual Studio
    - Right-click on project dependencies
    - Select manage Nuget packages
    - Search `numberToWordConverter-m88`
    - Click install
    - After installing, add to your project dependencies
    - Import the namespace  'using numberToWordConverter'
    - It has a single 'Converter' class and a static 'NumberToWords'   method 
    - The 'NumberToWords' takes in an integer and returns a string

### Prerequisites
  - An understanding of C# and NuGet Packages
  - A Code Editor

### Usage
```
using numberToWordConverter;

namespace ConsoleApp
{
    internal class Program
    {
        static void Main(string[] args)
        {
    int number = Convert.ToInt32(IntegerToConvert);
 string output = Converter.NumberToWords(number);
 Console.WriteLine(output);
        }
    }
}
```
## Authors

👤 **Henry Ugochukwu**

- GitHub: [@Henrymenez](https://github.com/Henrymenez)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/Henrymenez/NumberCoverterToWord/issues).


## Show your support

Give a ⭐️ if you like this project!
