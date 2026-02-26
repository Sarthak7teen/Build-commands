crave -n clone create --projectID 93 crave-devspaces/Munch

cd Munch

crave run --no-patch -- "curl https://github.com/Sarthak7teen/build-script/blob/main/build.sh | bash"