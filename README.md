# Design history for GOV.UK services

A place for us to document our service designs for the GOV.UK Family Experience service.

<https://family-exp-design-history.herokuapp.com/>


## Set up

Clone this project using Git. New to Git? Here is more [information about cloning a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)

Use Terminal to navigate to the directory and run npm install.

If the install is successful, run npm start. If there are erros, follow the prompts to debug then.

Follow the prompts in Terminal to open the design history in your browser. If the set up is successful it will be available at http://localhost:8080/.

## Writing an entry

Start with [the google docs template](https://docs.google.com/document/d/1Axk-IHSpwXuCzeopqvWbqwfRvKMqOU7WbSvC8PHeawg/edit?usp=sharing)

Get your entry reviewed by your peers.


## Adding an entry to the design history

Duplicate an existing entry. You will find them in the app /posts directory.

Give the .md file a unique name and date it to reflect when the work was done.

Once you have finished adding the content of the post, check it looks ok in your browser at http://localhost:8080/.

Raise a pull request. Here is more [information about pull requests.](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
Get the pull request reviewed by a peer.

Once the pull request is approved, merge it.

## Adding images

Take decent screen captures of your work.

Optimise the image file sizes using [TinyPNG.](https://tinypng.com/)

Create a directory for the images in /images.

The directory name needs to match your post name (besides the date).

Use the image macro to include an image in your post.

With caption:

```
{{ appFigure({
  image: {
    file: "file-name.png",
    alt: "A description of the image"
  },
  caption: "An optional caption"
}) }}
```

Without caption:

```
{{ appFigure({
  image: {
    file: "file-name.png",
    alt: "A description of the image"
  }
}) }}
```

## Example design histories

* [Becoming a teacher](https://bat-design-history.netlify.app)
* [Early years foundation stage framework](https://eyfs-design-history.netlify.app)
* [Get help with remote education](https://remote-education-design-history.netlify.app)
* [Get help with technology](https://ghwt-design-history.herokuapp.com)
* [Get Into Teaching](https://get-into-teaching-design-history.netlify.app)
* [Teacher CPD](https://teacher-cpd-design-history.herokuapp.com)
* [TRA Digital](https://tra-digital-design-history.herokuapp.com)
* [Submit data on social housing sales and lettings (aka CORE)](https://core-design-history.netlify.app)
* [Manage supervisions](https://ms-design-history.herokuapp.com)

## Technical notes

The design history uses the [GOV.UK Design System](https://design-system.service.gov.uk) and the [Heroku](https://www.heroku.com/) 
