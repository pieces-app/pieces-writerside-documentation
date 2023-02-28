# Pieces for Developers Jetbrains Plugin - Writerside Documentation

### Built with:
- [Jetbrains Marketplace Documentation](https://plugins.jetbrains.com/docs/marketplace/documentation-page.html#create-documentation-for-your-plugin)
- [Writerside Plugin Documentation](https://plugins.jetbrains.com/plugin/20158-writerside)

### How to get started with this repo: 
> 1) Make sure that you have [Intellij](https://www.jetbrains.com/idea/download/#section=windows) Installed (community or ultimate works just fine)
> 2) Download the Writerside Plugin and install it from the link above 
> 3) Clone the repo here onto your local machine 
> 4) Follow along with the documentation on the [writerside plugin](https://plugins.jetbrains.com/plugin/20158-writerside/docs/getting-started.html), and you'll see the steps needed to create an instance and start to create topics. 
> 
> Some Additional Info: 
> 1) To actually view the pages that you are creating from their Markdown format - you have two options:
>   1. You can **View it from inside of your Intellij Editor**
>      1. Once you have a few pages and items created, you can open the Writerside Plugin, right-click on the topic that you would like to view and select "Preview Topic"
>      2. **NOTE** This is the best option as it will update live as you update it and react to changes
>   2. You also can launch this by running a http-server locally 
>      1. Download and install http-server (recommending that this id done with NPM but can also be done via .zip file) [from this link](https://www.npmjs.com/package/http-server)
>      2. *you also can just run ```npm install --global http-server``` to have access to this local server configuration globally or using brew ```brew install http-server```
>      3. Once you have this installed you can run that server with the ```http-server``` command at the projects file location on your computer 
>      4. [There are specific instructions for this configuration here](https://plugins.jetbrains.com/plugin/20158-writerside/docs/local-build.html)
>
> 2) Images are stored in the /images folder, and this supports .gifs 
> 3) **If you generate the .zip file be sure to omit it from your github commits and pushes due to file size restraints**.
> 
> :)