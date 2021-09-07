# lbrs
Python Logging Information Based Response System (LBRS):
-Key Points:
    The latest version of Python is required to run this program.

    As stated in the Python Watchdog Documentation, the Windows file system differs to Linux
    as such renaming events are considered movement events. Due to the way the Windows OS polls watched directories

    The Python Watchdog API will need to installed before running the program as it makes use
    of its libraries. Methods of installation can be referred to in the Watchdog Documentation.

    For Watchdog API installation on Windows, ensure Linux terminal has been installed. Follow this
    link: https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/
    for further help.

    Watchdog Documentation Link: https://pythonhosted.org/watchdog/index.html

-Dependencies
    -Watchdog
    -Easy GUI
    -Smtplib
    -PyFPDF

-Important To Note
    LBRS Makes use of your Gmail account to send reports of file system events to itself.
    To ensure the LBRS can correctly login, ensure less secure apps is enabled under privacy settings
    You may want to create a spare or throwaway Gmail account for this to work, also ensure the login information provided
    is correct else the program will not be able to email reports to the user.

    A PDF and Text file for the Report and Logfile respectively need to be created prior to running th program also.

    More information: https://support.google.com/accounts/answer/6010255?hl=en
                      https://docs.python.org/3/library/smtplib.html
                      http://easygui.sourceforge.net/
                      https://pyfpdf.readthedocs.io/en/latest/
