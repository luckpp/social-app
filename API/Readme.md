- Run the project with no hot reload:
`dotnet watch run --no-hot-reload` (`run` is optional)

- Create a migration: `dotnet ef migrations add "added support for password data"`

- Run DB update after a migration has been added: `dotnet ef database update`