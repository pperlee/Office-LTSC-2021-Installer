## Office-LTSC-2021-Installer

I got this from internet. for windows only. It helps me download Office LTSC 2021 Chinese language version. 
Download all files to your disk, and run the following command with command line tool (e.g. Windows Terminal).

### download with command:

> setup.exe /download downloadconfig.xml

for change app language, edit downloadconfig.xml and replace:

> zh-cn

to other [language](https://docs.microsoft.com/en-us/deployoffice/office-deployment-tool-configuration-options#language-element).

### setup apps before install:

> setup.exe /configure installconfig.xml

if language changed when you download files, you must edit installconfig.xml and replace:

> zh-cn

to other [language](https://docs.microsoft.com/en-us/deployoffice/office-deployment-tool-configuration-options#language-element).

## Microsoft Official Link

[Deploy Office LTSC 2021](https://docs.microsoft.com/en-us/deployoffice/ltsc2021/deploy)

[Office Deployment Tool](https://www.microsoft.com/download/details.aspx?id=49117)

## enjoy.
