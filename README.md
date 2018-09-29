# Nostalgia

Enter the date you wish to go back to and the program will show you what you may have seen.

It is a sort of time machine.

## Usage

Outputs in human-readable or JSON (-j flag in CLI).

API outputs based on Accept header (text/plain, text/html or application/json).

Change the locale using 

CLI e.g.: 

$ nostalgia 2000-01-01

API e.g.:

Accept: application/json
GET /nostalgia?date=2000-01-01

{
}

## Types of output

Software
    Most popular GNU/Linux distributions
    Most popular "other" distributions of operating systems such as BSD or Solaris

Computing
    Most popular / recent computing brands
    Most popular / recent computing trends

Politics
    Prime ministers (of the UK of course)
    Monarchs (of the UK of course)