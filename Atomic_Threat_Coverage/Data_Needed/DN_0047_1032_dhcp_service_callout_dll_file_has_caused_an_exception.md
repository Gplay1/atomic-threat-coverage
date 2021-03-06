| Title             | DN_0047_1032_dhcp_service_callout_dll_file_has_caused_an_exception                                                                                                      |
|:------------------|:-----------------------------------------------------------------------------------------------------------------|
| Description       | The installed server callout .dll file has caused an exception                                                                                                |
| Logging Policy    | <ul><li> Not existing </li></ul> |
| Mitigation Policy | <ul></ul> |
| References     		| <ul><li>[https://docs.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/cc726937(v%3dws.10)](https://docs.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/cc726937(v%3dws.10))</li></ul>                                  |
| Platform       		| Windows   |
| Type           		| Windows Log 		| 
| Channel        		| System    |
| Provider       		| Microsoft-Windows-DHCP-Server   |
| Fields         		| <ul><li>EventID</li><li>Computer</li><li>Hostname</li></ul>                                               |


## Log Samples

### Raw Log

```
- <Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
  - <System>
    <Provider Name="Microsoft-Windows-DHCP-Server" Guid="{6D64F02C-A125-4DAC-9A01-F0555B41CA84}" EventSourceName="DhcpServer" /> 
    <EventID Qualifiers="0">1032</EventID> 
    <Version>0</Version> 
    <Level>3</Level> 
    <Task>0</Task> 
    <Opcode>0</Opcode> 
    <Keywords>0x80000000000000</Keywords> 
    <TimeCreated SystemTime="2019-07-11T15:48:53.000000000Z" /> 
    <EventRecordID>551</EventRecordID> 
    <Correlation /> 
    <Execution ProcessID="0" ThreadID="0" /> 
    <Channel>System</Channel> 
    <Computer>atc-win-2k12</Computer> 
    <Security /> 
  </System>
  - <EventData>
    <Data>%Exception details%</Data> 
    <Binary>7E000000</Binary> 
  </EventData>
</Event>
```




