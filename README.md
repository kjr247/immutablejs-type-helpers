<h1 align="center">
  <img src="https://i.imgur.com/tuepUj3.jpg" height="150" width="150"/>
  <p align="center">immutablejs-type-helpers</p>
  <p align="center" style="font-size: 0.5em"> Delightfully sweet helpers for ImmutableJs.</p>
</h1>

A set of functional helpers to assist with type checking, getting, defaulting, etc. with Immutable.js and TypeScript

# Motivation

Ever .toJS() something because you aren't sure of what you are dealing with? This is so common for new comers and vets alike. But just one gotcha just to start us off is well if your data was a List or a Set you get an array... no matter what... in the end you pour your time over the docs and realize they offer some types and some type checking methods, but perhaps you expected some value to exist and be a valid immutable type and allow a default. These utils stream line all of these things saving you time, frustraion, and confusion.
