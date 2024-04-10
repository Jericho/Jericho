From time to time I publsih beta versions of the Open Source projects that I maintain to give collaborators access to new feature I am working on or to give them the ability to validate functionality, bug fixes, etc. I publish these package on my personal Feedz.io nuget feed.

The NuGet v3 URL for this repository is: `https://f.feedz.io/jericho/jericho/nuget/index.json`

If you are using Visual Studio, you can add this feed by following these steps:
1. Open Visual Studio.
2. Go to Tools > Options.
3. Expand the NuGet Package Manager section, and then select Package Sources.
4. Click the green (+) sign to add a source.
5. Enter the `Jericho's prsonal nuget feed` as the Name and use `https://f.feedz.io/jericho/jericho/nuget/index.json` for the Source URL.
6. Select OK when you're done.

To use the feed:
1. Right-click on your project in the Solution Explorer, then select Manage NuGet Packages....
2. Select Browse, and then select your new feed from the Package source dropdown menu.
3. Use the search bar to look for packages in your feed.
