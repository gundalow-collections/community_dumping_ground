 Role

This is an example single Collection called `community.collection_dumping_ground`.

This Collection is a *proposal* for the default location for all Community Content that was previously in ansible/ansible that doesn't have an explicit home.

A similar directory structure to ansible/ansible is used, ie:
`plugins/modules/database/mongodb/`

As this is an independent Collection, it can be release on it's own release cadance.

It will also be listed as a dependency of the `ansible.kitchen_sink` Meta collection

If in the future there is an active Working Group that wishes to take over control of a subset of this Collection, it could be span out into it's own Repo & Collection, see [grafana collection](https://github.com/gundalow-collections/grafana/) for an example, and a `tombstone link` would be added to redirect to the new Collection.

## GitHub workflow

* Maintainers would be members of this GitHub Repo
* Branch protections could be used to enforce 1 (or 2) reviews from relevant maintainers [CODEOWNERS](.github/CODEOWNERS)

## Notes

*WARNING* This is a proof of concept for Ansible Community Collection development workflow.

For more information see `#ansible-community` on Freenode IRC.


## License

GNU General Public License v3.0 or later

aee LICENCING to see the full text.
