### Hi I'm Javokhirbek Khaydarov👋

I'm frontend developer <br/>
### My activities 
[![javohirbekkhaydarov's github stats](https://github-readme-stats.vercel.app/api?username=javohirbekkhaydarov&show_icons=true&theme=react)](https://github.com/javohirbekkhaydarov/github-readme-stats) <br/><br/>

### Using languages
![ ](https://github-readme-stats.vercel.app/api/top-langs/?username=javohirbekkhaydarov&show_icons=true&theme=react)
name: Add contributors
on:
  schedule:
    - cron:  '20 20 * * *'
# push:
#   branches:
#     - master

jobs:
  add-contributors:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v2
    - uses: javohirbekkhaydarov/add-contributors@main
      with:
        CONTRIBUTOR: '### Contributors'
        COLUMN_PER_ROW: '6'
        ACCESS_TOKEN: ${{secrets.GITHUB_TOKEN}}
        IMG_WIDTH: '100'
        FONT_SIZE: '14'
        PATH: '/README.md'
        COMMIT_MESSAGE: 'docs(README): update contributors'
        AVATAR_SHAPE: 'round'
📍    I'm Current location: Samarkand, Uzbekistan  </br>
📝  Ask me about anything, I am happy to help) </br>
📨  My telegram blog <a href="https://t.me/javohirbek_frontEnd">link</a>
