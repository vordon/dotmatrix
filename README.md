# Dot Matrix

#### Usage

```bash
go get -u github.com/kevin-cantwell/dotmatrix
```

Sample input image:

![](face.jpg)

Usage and output on a terminal of width 80:

```bash
$ dotmatrix < face.jpg
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠁⡀⢸⣀⢄⠁⠀⣃⢀⡀⠀⠀⠀⠀⠄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠂⠋⢾⣧⠀⣿⣠⣇⡆⣶⡄⠌⡀⢀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠢⢜⣿⣾⣿⣿⣿⣷⣿⣿⡞⣠⠁⠀⢀⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⢊⠄⣀⣬⣬⣤⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⢀⡴⢄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠉⠛⣿⣿⣿⣿⣿⣿⣿⣿⣤⢄⢞⣤⡖⣀⠀⠀⠀⠀⠀⠀⠀⠀⠁⣿⣽⣫⣵⣄⣤⠦⠀⠀⠀⠀⠀⠀⠠⢆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠠⠖⢠⡤⢀⠀⠀⠀⢀⠁⠐⢤⣢⢢⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣾⣿⣆⡀⠀⠀⠀⠀⠀⠀⠀⢻⣽⢿⣿⣿⣿⣲⣦⠀⠀⠀⠀⠀⠀⣹⠅⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⣠⡿⣴⣿⣒⠀⠈⣈⣑⣮⣶⣷⣷⣿⣶⣷⣦⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣇⠀⠀⠀⠀⠀⠀⠀⠘⣿⣿⣿⣿⣿⣿⣳⣄⠀⠀⠀⠀⠀⠘⡁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠉⠀⠉⠚⢿⣗⣧⠭⠿⣶⣿⣿⣿⣿⣿⣿⣿⣿⣷⣦⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠛⢿⣿⣿⣿⣿⣿⣿⣿⣿⣶⡀⠀⠀⠀⠀⠀⠀⢹⣿⣿⣿⣿⣿⣟⡯⠀⠀⠀⠀⠀⠘⣷⠆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠐⠒⢶⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣤⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⢿⣿⣿⣿⣿⣿⣿⣿⣷⡀⠀⠀⠀⠀⠀⠈⢹⣿⣿⣿⣿⣿⣷⡀⠀⠀⠀⠀⢸⣿⣉⣀⠀⠉⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠙⠻⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣦⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⢿⣿⣿⣿⣿⣿⣿⣷⡆⠀⠀⠀⠀⠀⠈⣿⣿⣿⣿⣿⣿⡇⠀⠀⠀⠀⢸⣿⡟⡛⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠙⠻⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣤⡀⠀⠀⠀⠀⠀⠀⠀⠀⠙⢿⣿⣿⣿⣿⣿⣿⡄⠀⠀⠀⠀⠀⠘⣿⣿⣿⣿⣿⣇⠀⠀⠀⠀⣼⣿⢿⣿⡆⠀⠀⠀⠀⠠⡄⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠙⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⣄⠀⠀⠀⠀⠀⠀⠀⠈⠻⣿⣿⣿⣿⣿⣷⡄⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⠀⠀⠀⠀⣿⣿⣿⣿⣯⠀⠀⠀⠀⠘⡿⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠙⠻⢿⣿⣿⣿⣿⣿⣿⣶⣄⠀⠀⠀⠀⠀⠀⠀⠙⣿⣿⣿⣿⣿⣷⠀⠀⠀⠀⠀⠈⣿⣿⣿⣿⣿⠀⠀⠀⠀⣿⣿⣿⣿⡏⠀⠀⠀⠀⡰⠄⠀⠀⠀
⠀⠀⠀⠀⢀⣤⣴⣄⣶⣾⣿⣿⣿⣿⣿⣶⣶⣤⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠻⣿⣿⣿⣿⣿⣿⣷⣄⠀⠀⠀⠀⠀⠀⠈⢻⣿⣿⣿⣿⣧⠀⠀⠀⠀⠀⣿⣿⣿⣿⣿⠀⠀⠀⢀⣿⣿⣿⣿⡀⠀⠀⠀⢀⡍⠀⠀⠀⠀
⠀⠀⠀⠀⠸⠿⢿⡿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣶⣤⣤⣀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠻⣿⣿⣿⣿⣿⣷⣄⠀⠀⠀⠀⠀⠈⣿⣿⣿⣿⣿⡆⠀⠀⠀⠀⣿⣿⣿⣿⣿⠀⠀⠀⢸⣿⣿⣿⡟⠁⠀⠀⢀⡎⠁⠀⠀⠀⠀
⣿⣶⡀⠀⠀⠀⠁⠈⠁⠈⠉⡛⠛⠛⠛⠿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣦⣤⣀⠀⠀⠀⠀⠀⠀⠈⠛⢿⣿⣿⣿⣿⣷⡄⠀⠀⠀⠀⠘⣿⣿⣿⣿⣇⠀⠀⠀⠀⣿⣿⣿⣿⣿⠀⠀⠀⣸⣿⣿⣿⠀⠀⠀⠠⢿⡇⠀⠀⠀⠀⠀
⠋⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠙⠛⠻⢿⣿⣿⣿⣿⣿⣿⣿⣦⣤⡀⠀⠀⠀⠀⠀⠙⢿⣿⣿⣿⣿⣤⠀⠀⠀⠀⠘⣿⣿⣿⣿⠀⠀⠀⠀⣿⣿⣿⣿⡏⠀⠀⠀⣿⣿⣿⡟⠀⠀⣀⣋⠁⠁⠀⠀⠀⠀⢠
⠀⠀⠀⠀⠀⠀⠀⠀⢠⣄⣀⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠙⠻⢿⣿⣿⣿⣿⣿⣷⣤⡀⠀⠀⠀⠀⠙⢿⣿⣿⣿⣧⡀⠀⠀⠀⢻⣿⣿⣿⡇⠀⠀⠀⣿⣿⣿⣿⠇⠀⠀⢰⣿⣿⣿⠃⠀⣸⣿⠃⠀⠀⠀⠀⠀⣠⡿
⠀⠀⠀⠀⠀⠀⠀⣴⣿⣿⣿⣿⣿⣶⣶⣶⣤⣤⣄⡀⠀⠀⠀⠀⠀⠀⠀⠉⠙⠻⣿⣿⣿⣿⣿⣦⣄⠀⠀⠀⠀⠙⢿⣿⣿⣷⡄⠀⠀⠈⢿⣿⣿⣷⠀⠀⠀⣿⣿⣿⡿⠀⠀⢀⣾⣿⣿⡟⠀⢠⣿⡟⠀⢀⣤⠇⢀⣾⡟⠁
⠀⠀⣰⣦⠄⢠⣴⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣶⣤⣄⡀⠀⠀⠀⠀⠀⠈⠙⠛⢿⣿⣿⣿⣷⣦⡀⠀⠀⠈⠻⣿⣿⣿⣄⠀⠀⠸⣿⣿⣿⡀⠀⠈⣿⣿⣿⡇⠀⠀⣼⣿⣿⡿⠀⠀⣾⣿⠁⣴⣬⣿⠀⣸⠋⠀⠀
⠀⠀⣿⣿⢠⡿⣿⣿⠿⠛⠛⠛⠛⠛⠻⠿⢿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣶⣤⣄⡀⠀⠀⠀⠀⠉⠛⢿⣿⣿⣿⣦⡀⠀⠀⠙⣿⣿⣿⣆⠀⠀⣿⣿⣿⡇⠀⠀⣿⣿⣿⡇⠀⢀⣿⣿⣿⠃⠀⣼⣿⠇⣼⣿⣇⠁⠠⠋⠀⠀⠀
⠀⣼⣿⣿⣿⡿⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠙⠛⠿⢿⣿⣿⣿⣿⣿⣿⣿⣷⣦⣤⣀⠀⠀⠀⠉⠻⣿⣿⣿⣦⠀⠀⠈⠻⣿⣿⣄⠀⠸⣿⣿⡇⠀⠀⣿⣿⣿⠁⠀⣼⣿⣿⠋⠀⣼⣿⠋⣰⣿⡟⠈⠁⠀⠀⠀⠀⠀
⠀⣿⣿⣿⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠙⠛⠿⢿⣿⣿⣿⣿⣿⣿⣶⣤⣄⡀⠈⠙⢿⣿⣷⣤⠀⠀⠙⢿⣿⣦⠀⢹⣿⣷⠀⠀⣿⣿⡿⠀⢠⣿⡿⠛⣠⣼⡿⢃⣴⣿⡿⠃⠀⠀⠀⠀⠀⣠⣾
⠀⣛⡋⠀⠀⠀⠀⢀⣤⣤⣤⣤⣤⣤⣤⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⡀⠀⠀⠀⠈⠉⠉⠛⠛⠿⣿⣿⣿⣿⣶⣦⣄⡈⠛⢿⣷⣦⡀⠈⠙⢿⣧⡀⢻⣿⠆⠀⠿⠿⠀⢴⣿⠟⣁⣴⡿⢋⣴⣾⣿⡟⠁⠀⣴⣴⣄⣤⣾⣿⣿
⠀⠋⠁⠀⠀⠀⢠⣿⣿⣿⣿⣿⣿⣿⣿⣿⡯⠉⠉⠉⠀⠉⠉⠉⠉⠉⠉⠙⠒⠶⣦⣤⣤⣀⣀⡀⠈⠉⠛⠻⠿⣿⣿⣶⣤⣉⠙⠛⠂⠀⠈⠉⠁⠀⠀⠀⠀⠀⠀⡀⠀⠀⠀⣩⣥⣶⣾⡿⠛⠉⠀⠀⣰⣿⡏⢹⣿⣿⣿⣿
⠀⠀⠀⠀⠀⢀⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠤⠀⣠⣴⣷⣄⠠⣤⣤⠀⣤⣤⠀⠈⠉⠛⢿⣿⣿⣿⣿⣶⣶⣦⣤⣬⣭⣭⣭⡭⠔⠂⠀⠀⣴⣦⣀⠰⠤⠄⣠⣾⣿⣤⠄⠀⠉⠉⠉⠁⠀⠀⣀⣤⣶⣿⡿⠃⠘⣿⠟⠋⠁
⠀⠀⠠⣶⣶⣼⣿⣿⣿⣿⡿⠿⠛⠛⠛⠉⠉⠀⠀⠈⠙⠻⠿⣷⣶⣶⣿⣿⡿⠄⠁⠀⠀⠀⠈⠙⠛⠛⠛⠛⠛⠛⠛⠛⠛⣩⣴⣶⠟⢠⣤⠘⠛⠛⠛⠻⠿⠛⠛⠉⠀⣀⣠⣤⣴⣶⣶⣶⣿⣿⣿⣿⡟⠁⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠙⢿⣿⣿⡿⠋⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣤⣴⣿⣿⣿⣷⣶⣦⣴⣶⣶⣶⣶⣶⣶⣾⠛⠉⣠⣴⠞⣫⢖⡄⡀⡀⣐⢦⣬⣉⠛⠛⠛⠛⠛⠛⠉⠉⠉⠉⠉⠉⠁⠀⡀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠉⠉⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣠⣤⣤⣶⣶⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠟⠋⠁⣤⣾⢋⣵⠞⣩⢺⠗⣰⢧⢻⣆⠉⠛⢿⣶⣶⣶⣦⣤⣤⣤⣤⣤⣤⣤⣤⣶⡇⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣤⣤⣶⣶⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠿⠛⠛⠛⠉⠉⠉⠁⠀⢀⣤⣾⡟⢡⡿⢋⣾⢳⡟⢰⢹⡸⡌⢻⣷⣄⠀⠈⠉⠙⠛⠛⠛⠻⠿⢿⣿⣿⣿⣿⠁⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣴⣶⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠿⠛⠉⠀⠀⠀⠀⠀⠀⣀⣤⣤⣶⣾⣿⡿⠋⣤⡞⠁⣼⠃⣾⠇⢸⡘⣇⠛⣆⠙⢿⣿⣶⣤⣄⡀⠀⠀⠀⠀⠀⠀⠀⠀⠁⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⢼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠛⠋⠉⠀⠀⠀⠀⣀⣤⣶⣶⣿⣿⣿⣿⣿⣿⠟⠉⢠⣼⠟⠁⣼⡟⢰⣿⠀⢸⡇⢸⣆⠙⣦⡀⠙⠻⣿⣿⣿⣷⣦⣤⣄⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢿⣿⣿⣿⣿⣿⣿⠿⠟⠋⠉⠁⠀⠀⠀⠀⠀⣀⣤⣶⣾⣿⣿⣿⣿⣿⣿⡿⠟⠉⠁⠀⣰⣿⡟⠀⢰⣿⠃⣾⣿⠀⢸⣷⠀⣿⣆⠙⣷⣤⡀⠈⠙⠻⣿⣿⣿⣿⣿⣿⣶⣾⠆⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⣿⣿⡿⠟⠉⠁⠀⠀⠀⠀⠀⠀⠀⣀⣤⣶⣿⣿⣿⣿⣿⣿⣿⡿⠛⠉⠀⠀⠀⣠⣿⣿⡿⠁⢠⣿⡏⢠⣿⣿⠀⢸⣿⡆⠹⣿⣆⠘⢿⣷⣤⡀⠀⠈⠙⠻⣿⣿⣿⣿⡟⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠉⠀⠀⠀⠀⠀⠀⠀⠀⢀⣴⣾⣿⣿⣿⣿⣿⣿⣿⡿⠛⠉⠀⠀⠀⢀⣤⣾⣿⣿⡟⠀⠀⣸⣿⡇⢸⣿⣿⠀⠈⣿⡇⠀⢹⣿⡆⠀⠻⣿⣷⣦⡀⠀⠀⠀⠉⠉⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣴⣿⣿⣿⣿⣿⣿⣿⣿⠟⠉⠀⠀⠀⠀⣀⣴⣿⣿⣿⣿⠋⠀⠀⢀⣿⣿⠇⢸⣿⡏⠀⠀⣿⣷⠀⠈⣿⣿⡀⠀⠙⣿⣿⣿⣦⣄⠀⠀⠀⢠⠄⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣤⣶⣿⣿⣿⣿⣿⣿⣿⡟⠋⠁⠀⠀⠀⢀⠐⠾⠙⠻⣿⣿⠿⠃⠀⠀⠠⠚⠛⠋⣠⣾⣿⡇⠀⠀⣿⣿⡆⠀⠙⣿⣷⡄⠀⠈⠻⣿⣿⣿⣷⣶⣾⡿⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣤⣶⣿⣿⣿⣿⣿⣿⣿⣿⠟⠁⠀⠀⠀⠀⢀⣶⣿⣿⣶⣾⡶⠉⠉⠀⠀⣠⣶⣶⡶⠀⠀⣿⣿⣿⡇⠀⠀⢻⣿⣿⠀⠀⠸⣿⣷⣄⠀⠀⠈⠻⠿⠿⢿⠿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⣿⣿⣿⣿⣿⣿⣿⠏⠁⠀⠀⠀⠀⠀⣴⣿⣿⣿⣿⣿⣿⠃⠀⠀⠀⣼⣿⣿⣿⡇⠀⠀⣿⣿⣿⣧⠀⠀⠈⢿⣿⡇⠀⠀⢻⣿⣿⣦⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠹⣿⣿⣿⣿⡟⠁⠀⠀⠀⠀⠀⢠⣾⣿⣿⣿⣿⣿⡿⠁⠀⠀⠀⣴⣿⣿⣿⣿⠃⠀⠀⣿⣿⣿⣿⠀⠀⠀⠘⣿⣿⡄⠀⠀⢻⣿⣿⣷⣤⣀⠀⢀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⣿⣿⠉⠀⠀⠀⠀⠀⠀⣰⣿⣿⣿⣿⣿⣿⡟⠁⠀⠀⠀⢠⣿⣿⣿⣿⡟⠀⠀⠀⣿⣿⣿⣿⠀⠀⠀⠀⢻⣿⣿⡄⠀⠈⢻⣿⣿⣿⣿⣿⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠁⠀⠀⠀⠀⠀⢀⣶⣿⣿⣿⢿⣿⡿⠟⠀⠀⠀⠀⠀⣾⣿⣿⣿⣿⠃⠀⠀⢰⣿⣿⣿⣿⠀⠀⠀⠀⠘⣿⣿⣷⠀⠀⠀⠙⢿⣿⡿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⣾⣿⣿⣿⣷⣦⣤⠄⠀⠀⠀⠀⠀⣤⣬⣭⣭⣭⡍⠀⠀⠀⢠⣭⣭⣬⣥⠀⠀⠀⠀⠀⢻⣿⣿⣧⠀⠀⠀⠀⣨⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⣷⡄⠀⣰⣿⣿⣿⣿⣿⣿⣿⠋⠀⠀⠀⠀⠀⣰⣿⣿⣿⣿⣿⠇⠀⠀⠀⠀⣿⣿⣿⣿⡇⠀⠀⠀⠀⠈⣿⣿⣿⣧⠀⢀⣴⣿⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣷⣴⣿⣿⣿⣿⣿⣿⣿⠋⠀⠀⠀⠀⠀⣴⣿⣿⣿⣿⣿⡿⠀⠀⠀⠀⠀⣿⣿⣿⣿⣿⡄⠀⠀⠀⠀⠘⣿⣿⣿⠆⢺⣿⣿⣷⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⠋⠀⠀⠀⠀⠀⢀⣿⣯⣉⣉⣉⣉⠁⠀⠀⠀⠀⠀⣿⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⠸⠟⠁⠀⠈⠻⣿⣿⣧⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⡟⠁⠀⠀⠀⠀⠀⢠⣾⣿⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠀⣿⣿⣿⣿⣿⣿⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⣿⣿⣷⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡄⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⡇⠙⠁⠀⠀⠀⠀⠀⢠⣾⣿⣿⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠀⠹⣿⣿⣿⣿⣿⣿⡄⢀⣤⠀⠀⠀⠀⠀⠀⠀⠀⠙⢿⣿⣿⣦⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣤⣿⡁⠀⠀⠀⠀⠀⣼⣿⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⠀⢠⣾⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠀⠀⢻⣿⣿⣿⣿⣿⣷⣿⣿⣷⡄⠀⠀⠀⠀⠀⠀⠀⠈⢻⣿⣿⣿⣷⣦⡀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⢠⣴⣾⣿⣿⡟⠃⠀⠀⠀⠀⠀⣿⣿⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠀⠀⠈⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⡄⠀⠀⠀⠀⠀⠀⠀⠹⣿⣿⣿⣿⣿⣷⣤⠀⠀⠀⠀
⠀⠀⠀⣀⣴⣿⣿⣿⣿⣿⣿⠇⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⠀⠈⠛⢿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠀⠀⠀⠉⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⡀⠀⠀⠀⠀⠀⠀⠙⢿⣿⣿⣿⣿⣿⣿⣦⣄⠀
⢀⣴⣾⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠀⣼⣿⣿⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⢈⠉⠙⠛⠛⠛⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣤⠀⠀⠀⠀⠀⠀⠀⠻⣿⣿⣿⣿⣿⣿⣿⣧
⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠀⣿⣿⣿⣿⣿⣿⣿⣿⡆⠀⠀⠀⠀⠀⠀⠀⠀⠀⡁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣄⠀⠀⠀⠀⠀⠀⠘⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠀⠀⠀⠀⠀⠀⣿⣿⣿⣿⣿⣿⣿⣿⣷⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠲⣿⣶⣶⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣤⠀⠀⠀⠀⠀⠀⠙⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⢠⣿⣿⣿⣿⣿⣿⣿⣿⣿⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣹⣿⣿⣷⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣄⡀⠀⠀⠀⠀⠈⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⡏⠀⠀⠀⠀⠀⠀⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣤⣿⣿⣿⣿⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⡄⠀⠀⠀⠀⠈⢿⣿⣿
⣿⣿⠿⠿⠿⠿⠿⣿⡟⠁⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⣿⣿⣿⣷⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⡀⠀⠀⠀⠀⠈⢻⣿
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⣿⣿⣿⣿⣿⣦⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠟⠃⠀⠀⠀⠀⠀⠀⠉
⣀⣤⣤⣤⣄⣤⣤⣤⣀⢀⣀⡀⠀⠈⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⣿⣿⣿⣿⣿⣿⣷⣦⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⠻⣿⣿⣿⣿⣿⣿⣿⣤⣤⣤⣤⣤⣤⣤⣄⣀⣠⣤
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣦⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠙⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
```

You may also pass in a luminosity flag to adjust the sensitivity of the luminosity algorithm. A greater value will lighten the image, while a lower value will darken it:

```bash
# Darkens the resulting image 40% more than normal
$ dotmatrix -lum 10 < face.jpg
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠁⡠⠀⠀⢄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡠⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠁⠋⣂⠀⠀⠀⣄⠀⠀⠀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢙⠾⢤⣤⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠫⡲⡌⢢⣿⠋⣠⣷⢆⠀⠀⠀⠀⠀⠀⠀⠀⠁⠀⢀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣧⣿⣿⣿⣿⣶⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠁⠛⣿⣿⣶⣿⣿⣿⣧⡀⠀⠀⠀⠀⠀⠀⢡⡤⣅⡁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠠⡀⡊⣿⣿⣿⣿⣿⣿⣿⢦⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠺⣿⣿⣿⣿⣿⣧⠀⠀⠀⠀⠀⠀⠈⢿⣿⡷⠆⠈⡂⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠀⠛⠿⣿⣿⣿⣿⣿⣿⣿⣷⡤⡀⠀⠀⠀⠀⠀⠀⠀⠀⠙⣿⣿⣿⣿⣿⣧⡀⠀⠀⠀⠀⠀⠈⣿⣷⡄⠈⠂⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠉⠛⠿⣿⣿⣿⣿⣿⣿⣦⡄⠀⠀⠀⠀⠀⠀⠀⠈⢻⣿⣿⣿⣿⣇⠀⠀⠀⠀⠀⠀⣿⣿⠀⢈⠄⠀⠀⠀⠀⢁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠙⢿⣻⣿⣿⣷⣿⣦⣄⠀⠀⠀⠀⠀⠀⠀⠹⣿⣿⣿⣿⡆⠀⠀⠀⠀⠀⣿⣿⣦⣦⠂⠀⠀⠀⠀⠨⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠠⠀⠀⠉⣐⡤⢤⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠛⢿⣷⣿⣷⣿⣦⡄⠀⠀⠀⠀⠀⠀⢻⣿⣿⣿⣿⡀⠀⠀⠀⠀⢻⣿⣶⡇⡇⠀⠀⠀⠀⣃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⠂⢢⣴⣴⣶⣺⣦⣤⢄⡀⠀⠀⠀⠀⠀⠀⠀⠉⠻⣿⣿⣿⣿⣦⡀⠀⠀⠀⠀⠀⢻⣿⣿⣿⡇⠀⠀⠀⠀⣿⣿⣿⣷⠇⠀⠀⠀⠠⣳⡈⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠈⠚⠻⢿⣿⣿⢯⣿⣽⣖⣤⣄⠀⠀⠀⠀⠀⠀⠉⠻⣻⣿⣻⣷⡄⠀⠀⠀⠀⠈⣿⣿⣿⣧⠀⠀⠀⠀⣿⣿⣿⣿⠁⠀⠀⠀⡘⠾⠍⠂⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠙⠻⣿⣿⣿⣿⣷⣦⣄⠀⠀⠀⠀⠀⠉⠻⣿⣿⣿⣆⠀⠀⠀⠀⠹⣿⣿⣿⠀⠀⠀⠀⣿⣿⣿⣿⠀⠀⠀⠀⡿⣎⠈⠀⠀⠀⠄⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠤⢀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠛⢿⣿⣿⣿⣷⣤⡄⠀⠀⠀⠀⠙⠻⣿⣿⣧⡄⠀⠀⠀⢹⣿⣿⡇⠀⠀⠀⣿⣿⣿⡇⠀⠀⠀⣸⣃⠁⠀⠀⠀⣈⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠠⠀⣠⣬⣿⣶⣤⣄⣀⠀⠀⠀⠀⠀⠀⠀⠉⠙⠿⣿⣿⣿⣦⣄⠀⠀⠀⠀⠙⣿⣿⣧⡀⠀⠀⠀⣿⣿⣧⠀⠀⠀⣿⣿⣿⠇⠀⠀⢠⢭⣫⠁⠀⠀⡠⡁⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢙⡻⣟⣿⣷⣿⣷⣷⣶⣤⣄⡀⠀⠀⠀⠀⠀⠈⠉⠻⣿⣿⣷⣄⠀⠀⠀⠈⢿⣿⣿⡄⠀⠀⢹⣿⣿⠀⠀⠀⣿⣿⣿⠀⠀⠀⣾⡎⡅⠀⠀⠠⡱⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠉⠙⠻⠿⣿⢿⣿⣿⣿⣿⢦⣤⣄⠀⠀⠀⠀⠈⠙⢿⣿⣶⣄⠀⠀⠀⠙⣿⣷⡀⠀⠈⣿⣿⠀⠀⠀⣿⣿⡟⠀⠀⢰⣿⡏⠀⠀⢠⠃⠀⢀⠠⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠉⠛⠿⢷⣿⣿⣻⣿⣷⣤⣤⡀⠀⠀⠉⠻⣿⣦⣄⠀⠀⠉⠻⣷⡄⠀⠘⡿⡇⠀⠀⢹⣙⠅⠀⠀⠈⠛⠁⠀⠄⠈⠀⢤⢎⡋⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠉⠉⠛⠿⣟⣿⣷⣦⣤⡀⠀⠙⠻⣶⣄⠀⠀⠁⠛⠄⠀⠑⠂⠀⠀⠈⠁⠀⠀⠀⠀⠀⠀⠀⠀⡠⢄⡥⠊⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠉⠛⠻⠿⢷⣠⣄⠀⠁⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⡠⠑⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠑⡲⢶⣶⣤⣤⣤⣤⣀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⡤⡊⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠁⠀⠉⠉⠉⠉⠉⠋⠀⠁⢀⢤⠴⠂⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⡠⣤⣠⣤⡶⠶⡿⣛⡤⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣤⣔⣴⣀⠀⠀⢤⣤⣤⣤⣤⣤⣤⣴⡀⠁⠀⢀⡤⠒⢀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠉⠉⠉⠉⠉⠁⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣠⣤⣄⣴⣾⣶⣿⣾⣴⣀⠀⠀⠰⣿⣿⣿⡿⠿⠛⠉⠀⡠⡰⠋⡠⠂⠁⠀⠀⠀⠀⠰⡄⠈⠀⠶⢦⡤⣤⣤⣤⣤⣤⣤⣄⣄⣀⣤⡤⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣤⢤⣤⣴⣶⣷⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠟⠑⠀⠀⠈⠉⠉⠀⠀⠀⠀⡠⣐⠋⠁⠞⠁⡴⠃⠆⠀⠀⠀⡀⠘⣦⡀⠀⠀⠈⠉⠉⠙⠛⠛⠛⠿⠿⠧⠿⠃⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⠄⡄⠲⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠛⠉⠁⠀⠀⠀⠀⠀⠀⠀⣀⣤⣤⣶⣾⠟⠀⢠⠌⠀⡰⠀⢸⠀⢰⠀⠂⠑⠄⠉⠻⣖⣦⣤⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠁⠀⠀⠀⠉⠛⣿⣿⣿⣿⣿⡿⠿⠛⠋⠁⠁⠀⠀⠀⠀⠀⡠⠄⠀⠐⠂⣿⣿⣿⡿⠋⠁⠀⡤⠋⠀⣠⡇⠀⡏⠀⠘⡄⠈⡄⠀⣄⠀⠈⠚⢟⣿⣗⣖⠤⢄⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢂⡵⠛⠋⠉⠁⠀⠀⠀⠀⠀⠀⠀⣠⣤⡶⠝⠀⠀⠀⢀⢴⠞⠋⠉⠀⠀⣠⣬⡆⠀⢀⡟⠀⣸⡇⠀⠀⡇⠀⢻⡄⠈⢣⣄⠀⠀⠉⠛⠿⡶⡃⠀⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠁⠀⠀⠀⠀⠀⠀⠀⠀⢀⣤⣴⣿⣿⣿⡭⠀⠀⣀⠀⠃⠁⠀⠀⠀⢠⣾⣿⠏⠀⠀⣼⡃⠀⣿⡇⠀⠀⣷⠀⠈⢿⡄⠀⠻⣧⣄⠀⠀⠀⠉⠀⠀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣴⡻⣿⣿⣿⡿⠻⢠⠄⠀⠁⠀⠀⠀⠀⣠⣴⣿⣿⠏⠀⠀⢠⣿⡃⠀⣿⡇⠀⠀⣿⡇⠀⠘⡷⡄⠀⠙⡻⣣⢄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣤⠾⣿⣿⣿⡟⡻⣫⡿⠋⠁⠀⠀⠀⠀⠀⢠⣾⢿⣿⡟⠁⠀⠀⠀⡜⢿⠁⠀⢯⡇⠀⠀⣿⡇⠀⠀⢿⣣⠀⠀⠈⠊⠅⠀⠠⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠠⠀⠑⠝⠵⠊⡛⡛⣿⠏⠈⠀⠀⠀⠀⠀⠀⠀⠀⠈⠒⠛⠋⠁⠀⠀⠀⠀⠀⠀⠀⢰⣿⠇⠀⠀⢹⣿⠀⠀⠈⢿⣣⠀⠀⠀⠀⠄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠨⠊⠀⠀⠀⠀⠀⠀⠄⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣼⣾⣿⡆⠀⠀⠘⣿⢆⠀⠀⠈⡹⢅⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠠⠀⠀⠀⠀⠀⠀⠀⣠⠞⠋⠀⠀⠀⡀⠀⠀⠀⠀⠀⠀⠀⣤⠃⠀⠀⣿⣿⣿⡇⠀⠀⠀⢹⣿⡄⠀⠀⠙⡄⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡠⠛⠀⠀⠀⣦⠄⠀⠀⠀⠀⢠⢦⣶⣿⡾⠀⠀⠀⣿⣿⣿⡇⠀⠀⠀⠀⣿⣧⠀⠀⠀⠁⠁⠀⠄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠊⡀⠀⠀⢀⢷⠎⠀⠀⠀⠀⠀⣿⣿⣿⣿⠇⠀⠀⠀⣿⣿⣿⡇⠀⠀⠀⠀⠸⣹⢧⠀⠀⠀⠀⠀⠀⠀⠈⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠁⠀⠀⠀⠀⠀⠘⠛⠛⠛⠋⠀⠀⠀⠀⠋⠉⠈⠁⠀⠀⠀⠀⠀⢃⠌⡃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⠀⠀⠀⠀⠀⠀⠀⣀⣀⣀⣀⣀⡀⠀⠀⠀⠀⣀⣀⢀⣀⠀⠀⠀⠀⠀⠈⠆⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠁⠀⠀⠀⠀⠀⢠⣿⣿⣿⣿⣿⠁⠀⠀⠀⠀⣿⣿⠟⠻⠀⠀⠀⠀⠀⠀⠈⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠛⠟⠿⢿⠛⠇⠀⠀⠀⠀⠀⠉⠀⠀⠀⠣⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠄⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢤⢀⣤⣤⣤⣦⡄⠀⠀⠀⠀⠀⠀⢸⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡜⠒⠉⢻⣿⣿⣿⡇⠀⠀⠀⠀⠀⠀⠈⢷⡄⠀⠀⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠀⠀⠀⠿⢻⣿⡇⠀⠀⠀⠀⠀⠀⠀⠈⠈⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢹⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
```

#### How it Works

The input image (jpeg/gif/png) is decoded from stdin and resized to fit the terminal width. Then each pixel is mapped to a matrix of braille unicode points. The final image is written to stdout.

The terminal width determines the resolution of the output, so if you make your terminal wider you'll get a finer picture.

Each pixel is mapped to a monochrome color (black or white) depending on a fairly standard RGB luminosity algorithm.

The colors are inverted to work best on terminals with a black background.