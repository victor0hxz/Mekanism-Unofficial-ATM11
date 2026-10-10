## Version Locked 2.2

- Expanded the Resistive Heater input from seven to ten digits.
- Added `[heater].resistiveHeaterMaxEnergyUsage` to `config/Mekanism/general.toml`, measured in FE/tick. Default and maximum: 2,147,483,647. Restart after changing it.
- Enforced the configured limit on the server and clamped negative values safely.
- Verified 50 million FE/tick, the maximum buffer size and a lower server limit in an isolated server.

This is a targeted patch of the installed Version Locked 2.1 binary: only three classes are replaced. The repository includes the patch build and sources; the broader historical source snapshot has not been proven to reproduce the original binary.
