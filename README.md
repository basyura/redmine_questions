# redmine_questions

## Original

- [Redmine Q&A plugin](http://redminecrm.com/projects/questions/pages/1)
- https://github.com/RCRM/redmine_questions

## About

Plugin replaces Redmine Forums module with new UI and new features like tags, votes, page views.  
All Redmine forum features still work (notifications, email reply, sticked and closed topics).


## Install

```
bundle install --without development test
bundle exec rake redmine:plugins NAME=redmine_questions RAILS_ENV=production
```

## License

- GNU General Public License v2 (GPL).

## Changelog

- changed layout.
- added `include_content` search option.



