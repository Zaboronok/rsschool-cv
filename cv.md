## Yahor Zabaronak
### Contact info
- [Telegram](https://vk.com/zaboronok.egor)
- Phone: \+375(29)3202238
### Summary
- I'd like to change my vector development. I want to program to mobile devices.
### Soft skills
* C#
* asp.net
* mvc
* unit test
* SQL
* HTML/CSS
### Last code
```
private IConnectionSetupProvider _connectionSetupProvider;

private async Tasck OpenConnectionAndSetUpLib(DbConnection connection, UserConnectionInfo connectionInfo){
    await TryOpenDbConnectio(connection).ConfigureAwait(false);
    await _connectionSetupProvider.SetQLinl(connection, connectionInfo.Unit).ConfigureAwait(false);
    await _connectionSetupProvider.SetQDta(connection, connectionInfo.UserLogin).ConfigureAwait(false);
    await _connectionSetupProvider.SetTryMarker(connection).ConfigureAwait(false);
    await CheckSuspendDbConnection(connection);
}

public async Task CheckSuspendDbConnection(DbConnection connection){
    var isSuspend = await _connectionSetupProvider.CheckSuspend(connection).ConfigureAwait(false);
    if(!isSuspend) throw new DbConnectionException("Работа с базой данных временно недоступна");
}
```
### Experience
- Working in Alfa-Bank, developer ASP.NET. Had to work with .net Visual Basic / WinForms / WPF / MWWM. Developing a project **Доверительное управление**.
### Education
- BSU Faculty of Radiophysics and Computer Technology
### English
- Level A2. Completion Streamline course
