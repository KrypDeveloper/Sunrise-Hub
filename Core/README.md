# Sunrise Hub - Overview 🌅

Sunrise Hub provides a comprehensive collection of core functions that are essential for your projects. Most of these functions are open-source, making it easy for you to edit and update them as per your needs.

## Features
- Access to a rich and regularly updated database of information.
- Easily integrate Sunrise Hub’s functions into your projects.
- Open-source and customizable.

## How to Use 🚀

To use Sunrise Hub, your platform will require one of the following methods to make requests:
- **`request`**
- **`game:HttpGet`**

Once you’ve retrieved the data, you'll need a function to convert the returned JSON into a table. After this, you can use our vast and continually updated database in any project you’re working on.

### Example Usage
```lua
local core = "https://raw.githubusercontent.com/KrypDeveloper/Sunrise-Hub/refs/heads/main/Core/"
local response = game:HttpGet(core.. "OMNI%20X/data.json") --// Getting OMNI X database
local data = game:GetService("HttpService"):JSONDecode(response) --// Convert to table

-- Now you can use `data` in your project!
```
Updates & Contributions 🔄
We regularly update the functions and data available in Sunrise Hub to ensure you have access to the most accurate and useful information. Contributions are welcome! Feel free to fork the repo, make improvements, and submit a pull request.

License 📝
This project is open-source and available under the MIT License.

