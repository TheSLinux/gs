## Hello, world

This is an `empty` repository. The purpose is to provide a ticket system
for the `TheSLinux` projects. All tickets can be found at

* http://theslinux.org/bugs/all _(all open bugs)_
* http://theslinux.org/bugs/backlog _(the backlog items)_

## Ticket life-cycle

Each ticket often has a label. There are some important lables

* Important / Not-Important
* Critical / High or Low priority
* Backlogs / In progress

Normally, life-cycle of tickets is as below

1. Someone raises new ticket in `Backlogs`
2. Someone sets `Important` and `Priority` properties for the ticket
3. Someone picks the ticket and uses `In-Progress` label for it.
    * If the ticket is `Important`, and in `Critical` or `High Priority`,
      it should be picked before any other tickets
    * Some `Important` but `Not-Urgent` ticket may become very critical
      in the future. Please deal with them carefully
4. Someone closes the ticket
5. Someone re-opens the ticket, goto `1`.

## Time recording

`Github` doesn't record label changes, so please record label time
manually if such information is important.

## License

All tickets and ticktes' information/data belong to `TheSLinux` project,
and they are published under the license `CC BY-SA 3.0`.
