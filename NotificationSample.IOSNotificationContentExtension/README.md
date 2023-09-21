Add the next code to your app project:

```xml
<ItemGroup>
    <ProjectReference Include="..\NotificationSample.IOSNotificationContentExtension\NotificationSample.IOSNotificationContentExtension.csproj">
        <IsAppExtension>true</IsAppExtension>
        <IsWatchApp>false</IsWatchApp>
    </ProjectReference>
</ItemGroup>
```