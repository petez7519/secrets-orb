# secrets-orb
Orb Definition (orb.yml):
Defines an orb named my-orb.
Includes an executor using a Python Docker image.
Contains a command store-secret that stores a secret in the environment.
Defines a job example-job that uses the store-secret command and then prints the secret.
Configuration File (.circleci/config.yml):
Uses the my-orb orb.
Defines a workflow that runs the example-job from the orb.
This setup will store the secret my_secret_value in an environment variable named MY_SECRET and then use it in the job. Let me know if you need any more details or adjustments!
