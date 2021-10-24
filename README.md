![Dimo Logo](images/dimo-logo-small.png?raw=true "Dimo Logo")

# Dimo-OSS
Open source assets that make up the Dimo Pterodactyl app.

[Beta test with Testflight for iOS](https://testflight.apple.com/join/ICRyMFP1)

## About
Dimo is a native iOS mobile app allowing users to control their Pterodactyl servers on the go. The core application of Dimo is closed source at this time however parts of it will be shared here for open source use under the MIT license. Planned elements to be open sourced is the Swift based ANSI parser and the framework for creating extensions. This will also eventually be the home of the approved community extensions.

## Pterodactyl API Completion
This list tracks api feature completion. This does not mean that the UI element is in its final state, it just means it is functional in terms of api requests and usage. If something is not in this list it means it is not current planned.

<details>
  
#### ❌ Pterodactyl
- [x] List servers
- [ ] Show permissions

#### ❌ Account
- [x] Account details
- [ ] 2FA details
- [ ] Enable 2FA
- [ ] Disable 2FA
- [ ] Update email
- [ ] Update password
- [ ] List API keys
- [ ] Create API key
- [ ] Delete API key

#### ✅ Server
- [x] Server details
- [x] Console details
- [x] Resource usage
- [x] Send command 
- [x] Change power state

#### ✅ Databases
- [x] List databases
- [x] Create database
- [x] Rotate password
- [x] Delete database

#### ❌ File Manager
- [x] List files
- [x] Get file contents
- [ ] Rename file
- [ ] Copy file
- [x] Write file
- [ ] Compress file
- [ ] Decompress file
- [ ] Delete file
- [ ] Create folder

#### ❌ Schedules
- [ ] List schedules
- [ ] Create schedule
- [ ] Schedule details
- [ ] Update schedule
- [ ] Delete schedule
- [ ] Create task
- [ ] Update task
- [ ] Delete task

#### ❌ Network
- [ ] List allocations
- [ ] Assign allocation
- [ ] Set allocation note
- [ ] Set primary allocation
- [ ] Unassign allocation

#### ❌ Users
- [ ] List Users
- [ ] Create User
- [ ] User details
- [ ] Update user
- [ ] Delete user

#### ❌ Backups
- [ ] List backups
- [ ] Create backup
- [ ] Backup details
- [ ] Delete backup

#### ❌ Startup
- [ ] List Variables
- [ ] Update Variable

#### ❌ Settings
- [ ] Rename server
- [ ] Reinstall server
</details>
