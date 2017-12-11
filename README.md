# bamboo_remote_agent

Used to create a bamboo remote agent

Requirements
------------


Role Variables
--------------

- `cross_account_capability` - name of the capability for cross account access.
  This allows us to separate cross account access to separate clients
  e.g. `ACME AWS Cross Account`
- `publish_topic_names` - a list of topics that the AMI builder should be allowed
  to publish to.

### No longer supported

- `drupal_finalise_sns_topic_name` has been replaced by `publish_topic_names` to
  be more generic across accounts


Dependencies
------------

- docker

Example Playbook
----------------

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
