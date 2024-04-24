per installare:
go-service installare

per far partier:
go-service start

per visualizzare il log:
Get-EventLog -LogName Application -Newest 5 | Where-Object { $_.Source -eq "go-service" } 