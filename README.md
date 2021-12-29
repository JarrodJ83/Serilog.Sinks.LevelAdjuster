# Serilog.Sinks.LevelAdjuster
Serilog sink that allows for overriding the log level of any event that's written at runtime. Mainly useful for adjusting the level of logs from third party libraries which you do not control

## Credit
Cridit for this code goes to Nicholas Blumhardt's StackOverflow response on the issue of how to override the log level of a log emitted by a library you don't own: https://stackoverflow.com/questions/47036442/change-override-log-event-level-in-serilog
