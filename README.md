# PlaceOS - Edge

## Usage

1. Navigate to the backoffice interface of the desired PlaceOS instance you wish to connect Edge to
2. Note the domain (including protocol, eg. https://us.placeos.run for https://us.placeos.run/backoffice/)
3. Navigate to Manage Instance > Edges and click the Add New Edge button
4. Give your new Edge a name and description, click Save and note down the API Key that is temporarily displayed
5. In the docker-compose.yaml file within this repo, paste your key in under the `PLACE_EDGE_KEY` field and the instance URI in the `PLACE_URI` field
6. Run `docker-compose up -d`
