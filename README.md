# Badjao Inn — published builds

The Badjao Inn Management System, built and ready to install. Nothing else
lives here: the source is a separate, private repository.

**Hotel Badjao Inn · Rizal Avenue, Puerto Princesa City, Palawan**
Built by KViWorks.

## Installing it the first time

Download `BadjaoInn-Setup.exe` from the [latest
release](../../releases/latest) and run it. Windows will warn that the
publisher is unknown — the program is not yet signed with a Windows code
signing certificate. Choose **More info → Run anyway**.

Each release also carries `latest.json`, which lists the file's SHA-256. If
somebody handed you the installer on a USB stick rather than downloading it
here, check that number matches before running it:

```powershell
Get-FileHash .\BadjaoInn-Setup.exe
```

## Updating

You should not need this page again. From version 0.2.0 onwards the program
updates itself: **Settings → About & updates → Check now**, then **Install it
now**. It downloads from here, checks that KViWorks signed the file, and
installs it.

## What is in the installer

The reception program, the hotel's own network host, and the web pages the
tablet by the door and the desk phone use. No hotel data — a hotel's
reservations, guests and payments never leave its own computer except through
its own backups.
