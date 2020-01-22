# Visualize emergency service helicopters' operations over Toulouse

Record and visualize trajectories of emergency service helicopters over Toulouse from ADS-B data (provided by the [OpenSky Network](https://opensky-network.org/)) with the Python library [traffic](https://traffic-viz.github.io/).

Under the hood, data are stored with [pandas](https://pandas.pydata.org/) and maps are realized with [ipyleaflet](https://ipyleaflet.readthedocs.io/en/latest/)

Example: one week helicopters' operations in Winter 2020

![Toulouse SAMU helicopters](Toulouse_SAMU_helicopters.png)


## Running the tests

The entire code is available in the demo_toulouse_helicopters notebook

You can use it to generate a map in HTML with embed_minimal_html


## Built With
* [traffic](https://traffic-viz.github.io/) - Air traffic data processing in Python
* [pandas](https://pandas.pydata.org/) - Python Data Analysis Library
* [ipyleaflet](https://ipyleaflet.readthedocs.io/en/latest/) - Interactive maps in the Jupyter notebook


## Authors

* **Thomas Dubot & Xavier Olive** 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


## Acknowledgments

ADS-B data are provided by [The OpenSky Network](https://opensky-network.org/)



