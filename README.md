# Potlucky

Potlucky -- an app for planning potlucks.

Initial Idea:
- guests are sent email invitations to the event
- they follow the invitation to the site, where they can
-- view what is needed
-- view what is being brought already
-- sign up to bring something

- hosts can:
-- make a list of what they'd like guests to bring
-- view what guests are bringing
-- upload photos to use for their site

- username is: email address that the invitation is sent to
- hosts have username & password (pseudo-admin role)

- Database Model


## Getting Started

After you have cloned this repo, run this setup script to set up your machine
with the necessary dependencies to run and test this app:

    % ./bin/setup

It assumes you have a machine equipped with Ruby, Postgres, etc. If not, set up
your machine with [this script].

[this script]: https://github.com/thoughtbot/laptop

After setting up, you can run the application using [foreman]:

    % foreman start

If you don't have `foreman`, see [Foreman's install instructions][foreman]. It
is [purposefully excluded from the project's `Gemfile`][exclude].

[foreman]: https://github.com/ddollar/foreman
[exclude]: https://github.com/ddollar/foreman/pull/437#issuecomment-41110407

## Guidelines

Use the following guides for getting things done, programming well, and
programming in style.

* [Protocol](http://github.com/thoughtbot/guides/blob/master/protocol)
* [Best Practices](http://github.com/thoughtbot/guides/blob/master/best-practices)
* [Style](http://github.com/thoughtbot/guides/blob/master/style)
