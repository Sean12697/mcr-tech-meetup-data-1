# Manchester Tech Meetup Data (CompiledMCR Data)
 
Using the [Meetup API](https://www.meetup.com/meetup_api/) we have been able to gather raw data from the technology Meetup scene in Manchester. The purpose of curating this data is to assist the community by producing data analytics upon it, and also performing interesting data visualizations.

## Adding Experiments

If you wish to add to this project and visualize the data provided, you can do, follow the steps below then create a Pull Request.

1. You can create a script to generate the refined data you require by adding to the [_scripts](_scripts) folder of this project. Once done, when the website is generated your JSON file will be located in the `_site/data` folder.

2. Create a folder of your own in the [_static/pages](_static/pages) directory, in here place all of your HTML/CSS/JS and when pulling in the data, use `../../data/` as the relative location to your generated data. If you wish to use all of the data generated by this project, you can use `../../_data/` as your relative location (loading `groups.json`, `events.json` or `attendees.json`).

3. Once your page is in your new directory, add your project to [_pages.json](_pages.json), following the same format as the first item within the array. When this is done, you should be able to load the index file at the root of the _site folder and see your page under the "Experiments" section of the home page.