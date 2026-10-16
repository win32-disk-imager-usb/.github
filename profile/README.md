# Win32 Disk Imager - Write or Read a Raw Image on a Removable Disk

[![Open Win32 Disk Imager](https://img.shields.io/badge/Open-Win32_Disk_Imager-334155?style=flat-square&logo=windows&logoColor=white)](https://hiljakusumoto.github.io/.github/win32-disk-imager)

## At a Glance

You choose an img or a similar file, choose a drive letter, and write. Reading goes the other way: the stick becomes a file. The tool is small because the operation is a straight copy of sectors. It will not refuse a hard disk letter if you select one. You refuse it. Use it for the SD card or the USB stick you mean to erase.

- A file you trust
- A removable letter you have identified by size
- Write only when that stick may be erased
- Read when you need an image of a card you may copy
- A verify habit: eject, reinsert, and see the volume you expected

1. Insert only the target stick.
2. Confirm its letter and size in Explorer.
3. Select the image and that letter.
4. Write, or read into a new filename.
5. Do not open the image path on the same stick you are writing.

## Fits

SD cards and USB sticks, firmware cards, and simple img files. A poor fit for installing Windows from an ISO with a proper boot layout. A poor fit for a system disk. A poor fit if several sticks are plugged in and you are guessing letters.

## Requirements

| Item | Expectation |
|---|---|
| PC | Windows the build supports |
| Target | A removable disk you may erase |
| File | A complete image |
| Letter | Confirmed by size |

![Win32 Disk Imager with an image file and a small removable drive selected](https://www.digitalcitizen.life/wp-content/uploads/2026/03/windows-11-disk-imager.png)

## Fixes

Write fails immediately. The stick is in use or the letter is wrong.
The card is unreadable after a write. The image was not for that media, or the write was interrupted.
Read creates a huge file. You read the wrong disk. Delete that file once you are sure.
The letter changed after a reinsert. Look again before the next write.
You wanted a bootable multi-ISO stick. This is a raw writer, not a boot menu builder.

## The Letter Is the Whole Safety Check

Win32 Disk Imager will write the file you selected onto the letter you selected. Explorer's size column is how you know the letter is the SD card and not a backup disk that received a new letter this morning. Insert only the target. If the image is still downloading, wait. A successful write of a partial file is a card that will not boot and a tool that did nothing wrong.

Reading a card into an image is the reverse mistake: the file becomes as large as the card, and it lands wherever you pointed. Point it at a disk with room, and name it after the card. Eject before you pull the media. This program does not build a multiboot menu and does not turn an ISO into a careful Windows installer layout. It copies sectors. Use it when that is the job.

| Before write | Check |
|---|---|
| Only one removable disk | Unplug the others |
| Size matches the card | Not the internal disk |
| Image is complete | Not a browser partial |
| Path of the image | Not on the card itself |

## Letter and Size, Then Write

The drive letter is the device that will be overwritten. Insert only the SD card or stick, and match its size in Explorer. A backup disk that received a new letter this morning is an easy mistake. The image must already be complete. A partial download writes successfully and still will not boot. Do not store the image on the card you are writing.

Reading a card creates a file as large as the card. Point it somewhere with room and name it. Eject before you pull the media. This program does not build a multiboot menu and does not turn an ISO into a Windows installer layout. It copies sectors. Use it when that is the job. Never point it at the system disk.

- One removable device
- Size checked
- Image finished
- Image path not on the target
- Eject after
- Several sticks unplugged
- Boot tested on the kind of machine you will use

| Mistake | Result |
|---|---|
| Wrong letter | The wrong disk is erased |
| Partial file | A dead card |
| Read of a large card | A huge file you may not want |
| ISO of Windows | Not a careful USB install |

Look at the letter one more time after you think you are ready.

## Topic List

win32 disk imager, write img to sd, win32 disk imager usb, read sd card image, removable drive letter, raw image write, win32 disk imager verify, sd card img windows
