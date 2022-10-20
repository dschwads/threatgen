# threatgen
Individual Yaml files for threatgen tests


These indiviual yamls can be used to create k8s deployments intended to pull and run a threat generator intended to simulate various behaviors that would indicate bad actors.

Create namespace stg
Run each deployment by running kubectl apply -f <path to yaml> -n stg
  
The application will run and end in a "complete" phase, once complete the deployment can be deleted.
