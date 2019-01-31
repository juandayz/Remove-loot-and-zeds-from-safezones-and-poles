# Remove-loot-and-zeds-from-safezones-and-poles

1-Open your custom compiles.sqf and into !dedicated section paste this call. 

```ruby
player_spawnCheck = compile preprocessFileLineNumbers "dayz_code\compile\player_spawnCheck.sqf";//remove loot from safezones
```
2-the dayz_code folder provided here must be located in your mpmissions\your instance\
so the path looks mpmissions\your instance..chernarus..taki..whatever\dayz_code\compile\player_spawncheck.sqf
