# Test-IconDeserialiser

Repro for https://github.com/dotnet/winforms/issues/1825

The app is targeting .NET Framework 4.7.2 and .NET Core 3.0.
Run under .NET Framework the app is deserialising and loading both icons correctly, however run under .NET Core the app failing to render one of the icons correctly.

It appears to be struggling to correctly load the icon's information form a stream.
