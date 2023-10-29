- Run the project with no hot reload:
`dotnet watch run --no-hot-reload` (`run` is optional)

- Create a migration: `dotnet ef migrations add "added support for password data"`

- Run DB update after a migration has been added: `dotnet ef database update`

- in order to be able to run the debugger make sure that the .vscode folder contains:
  - launch.json
  - tasks.json
  - in case no file is present than use CTRL+SHIFT+P and search for <b>.NET Generate Assets for Build and Debug</b>