crave -n clone destroy Munch

crave -n clone create --projectID 35 Munch

cd Munch

crave run --no-patch -- "curl https://github.com/Sarthak7teen/build-script/blob/main/build.sh | bash"
