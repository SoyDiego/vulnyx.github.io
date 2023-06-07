# VulNyx

VulNyx is a website that contains a list of vulnerable machines that are Unix based.

Find the project at https://vulnyx.com

For more information on how to collaborate, see [submit](./submit.md).

If you wanna collaborate with code, PRs are welcome!

To run the web locally you need:

1. Clone the repository and navigate to the directory.

```sh
git clone https://github.com/VulNyx/vulnyx.github.io.git && cd vulnyx.github.io
```

2. Install Ruby and RubyGems on your system if they are not already installed.

```sh
sudo apt install ruby rubygems -y
```

3. You can check they are correctly installed with ```ruby -v``` and ```gem -v```.

4. Install the Jekyll and Bundler gems by running the command.

```sh
gem install jekyll bundler
```

5. Run the command ```bundle install``` to install any dependencies required by the project.

6. Once the dependencies are installed, run the command ```make serve``` to start the Jekyll server.

**NOTE** If the server does not start you can solve the problem with:

```sh
bundle update --bundler && bundle update && make serve
```

7. After the server has started, open a web browser and navigate to http://localhost:4000 to view the website.

8. Make any necessary changes to the code or content of the website and refresh the browser to see the changes.

9. To stop the Jekyll server, press <kbd>Ctrl</kbd> + <kbd>C</kbd> in the terminal.
