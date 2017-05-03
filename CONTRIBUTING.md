# Contributing

[Software Carpentry][swc-site] and [Data Carpentry][dc-site] are open source projects,
and we welcome contributions of all kinds:
new lessons,
fixes to existing material,
bug reports,
and reviews of proposed changes are all welcome.

## Useful Contributions to This Repository

* Do you have a question that's not answered in this "lesson"?  
* Did you notice an error, inconsistency, or spelling mistake in the lesson?  
* Do you have some materials that you would like to contribute, either: 
	* additions?
	* example files?
	* checklists?

For all of these, you can contribute using the methods listed below 
under "How to Contribute": direct email 
(if you can't get a GitHub account), adding an issue, or submitting a pull request.  Do 
whatever is comfortable for you.  

For those who are comfortable submitting pull requests, another way to contribute is 
to look through open issues and see if there are any that need a corresponding pull 
request to fix the problem.  "Claim" the issue by commenting on it and then go ahead 
and submit the pull request.  

Comments on issues and reviews of pull requests are just as welcome:
we are smarter together than we are on our own.
Reviews from novices and newcomers are particularly valuable:
it's easy for people who have been using these lessons for a while
to forget how impenetrable some of this material can be,
so fresh eyes are always welcome.

## Contributor Agreement

By contributing,
you agree that we may redistribute your work under [our license](LICENSE.md).
In exchange,
we will address your issues and/or assess your change proposal as promptly as we can,
and help you become a member of our community.
Everyone involved in [Software Carpentry][swc-site] and [Data Carpentry][dc-site]
agrees to abide by our [code of conduct](CONDUCT.md).

## How to Contribute

The easiest way to get started is to file an issue
to tell us about a spelling mistake,
some awkward wording,
or a factual error.
This is a good way to introduce yourself
and to meet some of our community members.

1.  If you do not have a [GitHub][github] account,
    you can [send us comments by email][contact].
    However,
    we will be able to respond more quickly if you use one of the other methods described below.

2.  If you have a [GitHub][github] account,
    or are willing to [create one][github-join],
    but do not know how to use Git,
    you can report problems or suggest improvements by [creating an issue][issues].
    This allows us to assign the item to someone
    and to respond to it in a threaded discussion.

3.  If you are comfortable with Git,
    and would like to add or change material,
    you can submit a pull request (PR).
    Instructions for doing this are [included below](#using-github).

## Where to Contribute

1.  If you wish to change this example lesson,
    please work in <https://github.com/swcarpentry/workshop-planning>.
    This lesson documents the format of our lessons,
    and can be viewed at <https://swcarpentry.github.io/workshop-planning>.

2.  If you wish to change the template used for workshop websites,
    please work in <https://github.com/swcarpentry/workshop-template>.
    The home page of that repository explains how to set up workshop websites,
    while the extra pages in <https://swcarpentry.github.io/workshop-template>
    provide more background on our design choices.

3.  If you wish to change CSS style files, tools,
    or HTML boilerplate for lessons or workshops stored in `_includes` or `_layouts`,
    please work in <https://github.com/swcarpentry/styles>.

## Using GitHub

If you choose to contribute via GitHub,
you may want to look at
[How to Contribute to an Open Source Project on GitHub][how-contribute].
In brief:

1.  The published copy of the lesson is in the [episodes][episodes] directory
    in the `gh-pages` branch of the repository
    (so that GitHub will regenerate it automatically).
    Please create all branches from that,
    and merge the [master repository][repo]'s `gh-pages` branch into your `gh-pages` branch
    before starting work.
    Please do *not* work directly in your `gh-pages` branch,
    since that will make it difficult for you to work on other contributions.

2.  We use [GitHub flow][github-flow] to manage changes:
    1.  Create a new branch in your desktop copy of this repository for each significant change.
    2.  Commit the change in that branch.
    3.  Push that branch to your fork of this repository on GitHub.
    4.  Submit a pull request from that branch to the [master repository][repo].
    5.  If you receive feedback,
        make changes on your desktop and push to your branch on GitHub:
        the pull request will update automatically.

Each lesson has two maintainers who review issues and pull requests
or encourage others to do so.
The maintainers are community volunteers,
and have final say over what gets merged into the lesson.

## Other Resources

General discussion of [Software Carpentry][swc-site] and [Data Carpentry][dc-site]
happens on the [discussion mailing list][discuss-list],
which everyone is welcome to join.
You can also [reach us by email][contact].

[contact]: mailto:admin@software-carpentry.org
[dc-issues]: https://github.com/issues?q=user%3Adatacarpentry
[dc-lessons]: http://datacarpentry.org/lessons/
[dc-site]: http://datacarpentry.org/
[discuss-list]: http://lists.software-carpentry.org/listinfo/discuss
[example-site]: https://swcarpentry.github.io/lesson-example/
[github]: http://github.com
[github-flow]: https://guides.github.com/introduction/flow/
[github-join]: https://github.com/join
[how-contribute]: https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github
[issues]: https://github.com/swcarpentry/workshop-planning/issues/
[repo]: https://github.com/swcarpentry/workshop-planning/
[swc-issues]: https://github.com/issues?q=user%3Aswcarpentry
[swc-lessons]: http://software-carpentry.org/lessons/
[swc-site]: http://software-carpentry.org/
[episodes]: _episodes
