# dtc-innovation.org

# Install

![Ruby][] has to be installed on your machine to build the project.

```bash
$ bundle install
```

# Run

```bash
$ bundle exec jekyll serve
```

Content will be available locally at [http://127.0.0.1:4000/]().

# Contribute Content

We use ![Netlify CMS][] to handle the

> https://dtc-innovation.org/admin/

# Data Models

## Customer

| Key | Description |
| --- | --- |
| `title` | -  |
| `website` | Website URL |
| `location` | Main country of the customer |

- title: Gironde County
- website: https://gironde.fr/
- location: France

## Project

To be found in `collections/_projects_{en,fr}/*.md`.
Available as a `site.projects` collection.

| Key | Description |
| --- | --- |
| `name` | - |
| `short_description` | - |
| `highlights_order` | Controls ordering on the Home _Project Highlights_ |
| `current_stage` | Definition of done of the current sprint |
| `next_stage` | Expectations about the next project milestone (mid-term) |
| `customer` | Related customer |
| `ressources[].name` | Resource name |
| `ressources[].url` | Resource URL |

[Ruby]: https://www.ruby-lang.org/
[Netlify CMS]: https://www.netlifycms.org/
