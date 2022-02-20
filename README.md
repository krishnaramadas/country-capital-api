# country-capital-api

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
This is an application programming interface written in Python and flask. 
This API returns the name of the country if a capital city is provided. 
The ASGI Server Uvicorn is used to serve this API. 
Also, there is a microservice endpoint for this API available at 
https://example.com/country-capital/[query-params] 
that can be used by any project in the organization to consume this API.


## Prerequisites
* Python 3.x
* virtualenv 
https://virtualenv.pypa.io/en/stable/
* Flask
   ```sh
   pip install Flask
   ```
* ASGI server Uvicorn
https://www.uvicorn.org/
<br>
https://www.uvicorn.org/settings/
or via
   ```sh
   pip install uvicorn
   ```
  
 ## Installation

1. Creating virtual emvironment
   ```sh
   python3 -m venv python-env
   ```
 2. Activate virtual environment
    On Windows
    ```sh
    python-env\Scripts\activate.bat
    ```
	On MaCOS or Unix
	```sh
     source python-env/bin/activate
    ```
3. Clone the repo in the virtual env
   ```sh
   git clone https://github.com/krishnaramadas/country-capital-api.git
   ```
4. Change directory into your local repo
   ```sh
   cd country-capital-api
   ```
5. Run Server
	 ```sh
     uvicorn example:app
     ```
6. Run the code
	```sh
     python api_code.py
     ``` 
7. Open browser to run
    http://localhost:5000

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage
This API can connect developers to software featuring data concerning countries around the world.
There is a microservice endpoint for this API available at
    ```sh
     https://example.com/country-capital/<query-params>
    ``` 
<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - Krishna Ramadas email- mail@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments


* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)

<p align="right">(<a href="#top">back to top</a>)</p>
