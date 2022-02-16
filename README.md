# Time Manager Application

This time management application was made to analyze the time spent on tasks on your computer.


## activity.py && autotimer.py 
Credit for these files goes to: https://github.com/KalleHallden/AutoTimer
These files were used from Kalle Halden's projects to create JSON structured objects with time spent on tasks.

## TimeManager.ipynb
The autotimer.py and activity.py files create an activities.json file. The following is an example of the activities entries, which is an array of objects:
```
    {
    "activities": [
        {
            "name": "autotimer.py - Visual Studio Code",
            "time_entries": [
                {
                    "days": 0,
                    "end_time": "2020-11-12 18:08:39",
                    "hours": 0,
                    "minutes": 0,
                    "seconds": 2,
                    "start_time": "2020-11-12 18:08:37"
                },
                {
                    "days": 0,
                    "end_time": "2020-12-11 11:44:40",
                    "hours": 0,
                    "minutes": 0,
                    "seconds": 15,
                    "start_time": "2020-12-11 11:44:25"
                },
            ]
        }
    }
```
TimeManager.ipynb was used to analyze the user application usage and create visuals based on what applications they used while doing the work or other tasks on their computers.

