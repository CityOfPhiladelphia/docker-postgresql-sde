This Dockerfile will have a postgres database ready and prepped to have ESRI database customizations placed on it by ArcGIS Desktop or Arc Pro products.

Warning!: This is very expeimental and in development and not intended for secure production databases. Running postgresql off a data directory in container memory is terrible for performance, but good for something to test against in ephemeral machines.
