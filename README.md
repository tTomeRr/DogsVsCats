# Flask-based Survey Application on Kubernetes
![DogsVsCats](https://github.com/tTomeRr/DogsVsCats/assets/129614080/792525da-1309-47cb-864a-67f9b0335ba3)

This mini-project deploys a Flask-based Application on Kubernetes using Kind. The application asks users for which animal they like more (a dog or a cat) and display the results in a graph. The deployment uses Bash scripting for logs, error handling and updating the Kubernetes cluster easily.

## Prerequisites

- Docker
- Kubernetes (Kind)
- Helm
- Python
- Linux machine

## Usage

All of the project can be managed by the deploy.sh script.

Flags:
- -i Install
- -d Uninstall
- -f <arg> Upgrading Flask replicas to have 1-5 replicas
- -m <arg> Upgrading Mongodb replicas to have 1-5 replicas
- -h Display help

```bash
EXAMPLE USAGES

# First, give the script executable permissions.
chmod a+x

# Installing the application-
./deploy.sh -i

# Deleting the application-
./deploy.sh -i -d

# Upgrading Flask and Mongodb replicas to 3 and 3-
 ./deploy.sh -i -f 3 -m 3
```

## Screenshots
![image](https://github.com/tTomeRr/DogsVsCats/assets/129614080/a0a41c23-1f11-48e9-ba76-e20a9aec42c9)
![image](https://github.com/tTomeRr/DogsVsCats/assets/129614080/e8678f3c-fcae-44f9-ae3b-c8ad61fbe854)



## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for any improvements or bug fixes.


## License

[MIT](https://choosealicense.com/licenses/mit/)
