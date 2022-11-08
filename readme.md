# Writing a paper in LaTeX with git

This repository is a template repository for writing papers in LaTeX. It contains some of the barebones structure you might want, and a collection of imports and convenience commands (like `\E{}` for expectation). It also has some guidelines and tutorials for the right workflow to make this type of editing work well, with justifications for why they are worth the effort.

# Why use git with GitHub instead of just Overleaf?

The basic reason to use git with GitHub instead of just using Overleaf is to keep track of document history in a sensible way, and to separate comments about the development of the paper from the actual LaTeX code of the paper itself. We also want to make use of the branches and pull requests features to get around the frustrations of editing each others' proofs and then having a hard time telling what was changed.

We can also make use of the GitHub issue tracker to keep track of changes that need to be made, instead of writing a comment that something needs to change inside of the actual LaTeX document.

The ideal is that the version of the paper in the main branch of the repository is always in a nice and readable state, without scratchpadding or scattered meta comments - it may be very incomplete, but what is in there should look like it is ready to be submitted.
