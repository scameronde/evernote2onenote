# Migrate Evernote to OneNote

## Why?
Because I use Evernote on a daily basis on multiple devices. Evernote is about to become
a paid service, and while I understand the necessity, I don't think that my usage pattern
(text and html only, mostly lookups) justifies the amount they plan to charge.

## Why OneNote?
I considered several options like Google Keep, Google Docs, EMail, DropBox, but EverNote
and OneNote both hit the spot for my needs.

I need a place where I can drop random information without fuss - a receipt for potato bread, 
esoteric git command line voodoo, inspiring quotes, drafts for articles, snippets from
web pages - and basically forget about them until I need them. Then I want to go to
that ONE place, type a search and have that information at hand. I do not want to
categorize, tag or format the information. I want a bin I can toss that into and look it
up when ever and where ever I need.

## My platforms
Android, iOS, Mac OS and Linux. No need for Windows.

## The conversion
Because I have collected information for more than 7 years with Evernote, I need to
be able to automatically export and import my notes. Luckily Microsoft has a tool that
does exactly that. There is one caveat with that tool: it only runs in Windows. So here
is what I had to do:

  - download a Windows 10 VM from http://modern.ie (they have VMs for VirtualBox)
  - start the vm and disable energy saving settings, or else the vm will shutdown
    after 10 minutes without keyboard entry or mouse movement
  - inside the VM install Evernote. OneNote is already preinstalled
  - download the converter tool from OneNote.com
  - create a OneNote account from within OneNote
  - start Evernote and synchronize your notes
  - start the converter and let it do its job
  
That is it. It took more than an hour (upload to the cloud seems to be slow at the moment)

## Running OneNote on Mac
After installing OneNote from the AppStore, I was disappointed at first. I could not
find my notes. It seems like I have to add every notebook from Evernote from your
Microsoft cloud drive to OneNote. ONE AT A TIME. That sucks, but it is a one time effort.

## Differences
Where Evernote has notebooks and notes, OneNote has notebooks, sections (tabs) and pages. 
Your notebooks get converted to notebooks, and your notes to pages. For 100 pages each the
converter will create a new section.

Especially the sections with the limit of 100 pages will make browsing your notes (or pages)
difficult. But you should not browse, you should search!

