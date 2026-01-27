# Life in Weeks

A visualization of a life lived in weeks, tracking meaningful events and the passage of time.

## Live Site

[weeks.brennan.day](https://weeks.brennan.day)

## About

This project visualizes a life as a grid of weeks, where each small box represents one week of life. Meaningful events are marked and annotated, creating a visual representation of how significant moments shape our journey through time.

Inspired by the concept popularized by Tim Urban's [Your Life in Weeks](https://waitbutwhy.com/2014/05/life-weeks.html) article.

## Technical Details

Built with Jekyll and hosted on Netlify. The visualization consists of:

- **Data file**: `_data/life-in-weeks.yml` - Contains all life events with dates, descriptions, and categories
- **Layout**: `_layouts/life-in-weeks.html` - Renders the week grid and handles event display
- **Base layout**: `_layouts/fullscreen.html` - Provides the fullscreen container
- **Includes**: `_includes/buster-head.html` and `_includes/header_fullscreen.html` - Shared HTML components

## Local Development

1. Install Ruby and Bundler
2. Run `bundle install`
3. Run `bundle exec jekyll serve`
4. Visit `http://localhost:4000`

## Customization

To create your own version:

1. Update `_data/life-in-weeks.yml` with your personal events
2. Adjust the `start_date` and `end_year` in `index.html` front matter
3. Customize colors and styling as needed

## License

MIT License - feel free to use this as inspiration for your own life visualization.
