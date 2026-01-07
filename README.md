# Exo-Finder

A locally hosted, full-stack web application exoplanet data analytics dashboard. Built using ReactJS, Recharts, and Bootstrap for the frontend, with a Python Flask Backend. Has a basic ETL file that gets data from NASA via a TAP query.


<img width="1868" height="866" alt="image" src="https://github.com/user-attachments/assets/aedc7958-2e83-4720-85b1-643c6e21e7f6" />


<img width="1861" height="856" alt="image" src="https://github.com/user-attachments/assets/85509bf5-3ab7-4daf-9ab2-88d1ab0cc3d6" />


<img width="1872" height="862" alt="image" src="https://github.com/user-attachments/assets/0b4adca7-030d-4a83-8773-13e2cef39fcb" />


### Features
- Search through the entire NASA database for a particular exoplanet, and view important data about it, such as its star, how it was discovered, its orbital radius, its discovery year, its mass, and its temperature.
- You can sort this table! Simply click a column header, and it will sort all the exoplanets according to that property. For example, clicking the radius column header will sort the exoplanets by radius in increasing order. Clicking again will sort in decreasing order.
- See through all this data at a glance in the visualization screen! It features 6 graphs based on all this data.

### Building and Deploying
To build the app, run
```
install npm
```
in the terminal. 

In order to update the database to include any newly discovered exoplanets, run
```
python exoplanet_etl.py
```

In order to deploy the backend, run
```
node exoplanet_backend.js
```

To deploy the frontend, run
```
npm start
```

Please report any bugs to me! Any feedback would be greatly appreciated for this personal project.
