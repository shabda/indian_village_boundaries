#Indian Village Boundaries (Maps)

Indian Village boundaries sourced from different government websites which are freely available to all the Indians. Here we have digitized them, cleaned them, added appropriate attributes so it can be used by all the researchers, students etc

The boundaries are organized by state using state ISO code. All the village boundaries are available in geojson (WGS84, EPSG4326) format. The below table gives you the status of the data as we clean and upload. Data is not perfect there as many errors both in data and boundaries. You can contribute by sending the pull requests. Please use the census names when correcting the attributes and geojson for shapes. Refer [CONTRIBUTING](/contributing) for ways to contribute.


<img width="250px" style="float:left" src="http://projects.datameet.org/logo/datameet_logo_v.1.2.png" > This projects run by <a href="http://datameet.org">Data{Meet}</a> community. DataMeet is a community of Data Science and Open Data enthusiasts. Data{Meet} community encompass many people, ideas, projects, solutions, and challenges that using data in India presents. Join the the <a href="https://groups.google.com/group/datameet">Google Group</a> to be part of this community.


## Structure
Each state has a folder with a short name, for example state of Gujarat will have GJ folder. It will contain a single geojson file gj.json and then a gj.md file containg the list of all supporting files.


## Attributes
Each boundary will have the following attributes

* NAME : Name of the Village/Town as per census
* TYPE: Village or Town
* SUB_DIST: Sub District name as per census
* DISTRICT : District name as per census
* STATE: State or UT name as per census
* CEN_2001: Code as per 2001 census, its a concatination of State Code, District Code, Sub-District Code, Village Code 2001.
* CEN_2011: Code as per 2011 census, We are yet to populate this. 

## States
For a view of each state map go to the state page. In state page you can see a very rough version of the state village map and notes related to that state map. You can also download the full version state map from state page. If you just want to download the map. <em>Right click on download link -> Save link as</em>.

<table class="table table-bordered">
	<thead >
		<td>State</td>
		<td>Status</td>
		<td>Download</td>
	</thead>
<tbody>
	<tr>
		<td><a href="/br" target="_blank">Bihar - BR</a></td>
		<td>Complete</td>
		<td><a href="https://github.com/datameet/indian_village_boundaries/raw/master/br/br.geojson" target="_blank">Download</a></td>
	</tr>
	<tr>
		<td><a href="/ka" target="_blank">Karnataka - KA</a></td>
		<td>Complete</td>
		<td><a href="https://github.com/datameet/indian_village_boundaries/raw/master/ka/ka.geojson" target="_blank">Download</a></td>
	</tr>
	<tr>
		<td><a href="/kl" target="_blank">Kerala - KL</a></td>
		<td>Complete</td>
		<td><a href="https://github.com/datameet/indian_village_boundaries/raw/master/kl/kl.geojson" target="_blank">Download</a></td>
	</tr>
	<tr>
		<td><a href="/ga" target="_blank">Goa - GA</a></td>
		<td>Complete</td>
		<td><a href="https://github.com/datameet/indian_village_boundaries/raw/master/ga/ga.geojson" target="_blank">Download</a></td>
	</tr>
	<tr>
		<td><a href="/gj" target="_blank">Gujarat - GJ</a></td>
		<td>Complete</td>
		<td><a href="https://github.com/datameet/indian_village_boundaries/raw/master/gj/gj.geojson" target="_blank">Download</a></td>
	</tr>
</tbody>
</table>

## License
All our work will be under [Open Data Commons Open Database License (ODbL)](http://opendatacommons.org/licenses/odbl/). This data is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  If you find issues we are more than happy to accept corrections but please source them to an official source. Refer [CONTRIBUTING.md](CONTRIBUTING.md) for ways to contribute.

## Issues

If you have any issues with the maps, please report them on the github repository:

<a href="https://github.com/datameet/indian_village_boundaries/issues/new"><button class="btn btn-primary" type="submit">Report Issue</button></a>
<a href="https://github.com/datameet/indian_village_boundaries/issues"><button class="btn btn-primary" type="submit">Active Issues</button></a>


## Repository
<a class="btn btn-lg btn-success" href="https://github.com/datameet/indian_village_boundaries">
  <i class="fa fa-github fa-2x pull-left"></i> GitHub</a>   <a class="btn btn-lg btn-success" href="https://gitlab.com/datameet/indian_village_boundaries">
  <i class="fa fa-git fa-2x pull-left"></i> GitLab</a>


## Community
