save git creds for pushing:
git config --global credential.helper '!f() { echo "username=YOUR_GITHUB_USERNAME"; echo "password=YOUR_GITHUB_TOKEN"; }; f'
git config --global user.name "Your GitHub Username"
git config --global user.email "Your GitHub Email Address"


tsdasdasd