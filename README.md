# Find Active Servers

There are about 55 servers in the list , with chat , movie , tv servers. Run the script to find which servers are accessible via your WiFi .

## Running the appilcation
### From prebuilt binary
1. Download executable from [releases](https://github.com/tasmirz/ISP_server/releases).
#### Advanced Usage
1. Download [servers.csv](https://raw.githubusercontent.com/tasmirz/ISP_server/main/servers.csv)
2. Drag the servers.csv on the executable
3. Download the updated servers.csv periodically
### From Source
1. Download this code as zip
2. Install Node.js if you haven't
3. Install dependecies 
```bash
npm install
```
4. Run the script using 
```bash
npm start
```
5. The list will be generated and stored in `working_url.txt` file.
#### Build From Source 
```bash
 npm run build
 ```
>Find built executables for Linux and windows on `build` directory
## Contibuting
1. Fork this repo
2. Add your servers to the [server.csv](./servers.csv) file (you can edit it with MS Excel)
3. Push and submit a pull request.
