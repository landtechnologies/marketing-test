# Landtech Technical test

At LandTech we use articles as part of our conversion funnel. Marketing are interested in seeing which articles are performing well, and which articles need to be tweaked to increase conversion rate.

For this technical task we've provided some mock data to get you up and going (found in `data.json`) but imagine in production this would be coming from some sort of api. The data contains a collection of `articles` & `authors`. We have also included a directory of author images (`images/authors/[authorId].jpg`).

**Considerations**:

- We use a mixture of PHP & JS in the marketing team. We are looking to prove with this technical test that you can come in & hit the ground running with our PHP based marketing site.
- Don't worry about styling. However, we are interested in seeing the data rendered in a meaningful way.
- Don't forget include any relevant documentation about how to run the app locally.
- Please spend no longer than 2hrs working on this technical task. If you find yourself running out of time - feel free to capture your 'next steps' in a README with your submission.

### Task

1. Render the list of articles from `data.json` showing:

   - Title linking to the article's url.
   - Article published date in `dd/mm/yyyy` format.
   - Author details including author name & avatar.

1. Calculate and render a conversion rate percentage next to each article. Use the following thresholds to make it easy to see at a glance which articles are performing well.

   - Anything less than 8 show as red.
   - Anything less than 10 show as yellow.
   - Anything 10 or above show as green.

1. Elsewhere on the page create a table of authors and order them based on their published article's conversion rate. The table should include the following:

   - Author name
   - Number of published articles
   - Average conversion rate for articles
