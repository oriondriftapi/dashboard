
# ![API Dashboard](OD_API_IMAGE_SMALLER.png) API Dashboard

## Summary
C++ and ImGui based dashboard app surrounding Orion Drift's API.

## Getting Started
1. Clone the repository
   ```powershell
   git clone https://github.com/oriondriftapi/dashboard.git
   ```
2. Before opening the .sln file, confirm you have a version of Visual Studio downloaded, this could be either Visual Studio 2022 -> Visual Studio 2026
3. Open the .sln file inside of your Visual Studio installation
4. After opening the project in Visual Studio, navigate to the 'build' tab on the toolbar and then build the solution
5. Go to the build directory (depends on if you build in DEBUG or RELEASE) and open the .exe generated

## How to Use

Once you run the ```.exe``` you compiled or downloaded from the repo, it will prompt you to "sign in".
You can continue as a guest, but you will be limited to only station viewing and fleet viewing.

If you want to sign in to the dashboard, please follow this YouTube video to get your API key:
https://www.youtube.com/watch?v=IPsDr3ZOE24

Once you get your API key, enter it into the input field above the "Login" button.
If you entered it correctly, you’ll be taken to a new page where you can view all the Stations, Fleets,
and Mothership information (the same data used by Orion Drift’s backend).

After logging in once, the Dashboard will give you the option to "Load the previous API Key used" on future launches. 

The previous API key is saved in the Windows Registry at:

```Programs\OrionDashboard\OD_API_KEY```

## Dependencies
- [imgui](https://github.com/ocornut/imgui)
- [json](https://github.com/nlohmann/json)
- [curl](https://github.com/curl/curl)

## How it works
The client side of the Dashboard (the application you open) talks to our javascript backend (i know this isnt very ideal lol), this is what all the stations, fleets, and players are retrieved from.

## Support
If you have any trouble compiling, downloading, or just general issues with the repo.
Please make an issue in the issues tab, or contact us on discord!

To contact us on discord please DM us at @oriondriftapi, or join our [discord server](https://discord.gg/v383ngramQ)
