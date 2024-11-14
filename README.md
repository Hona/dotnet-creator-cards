# Please note
The repository contains some cards based on an old file format. Please make sure to use the new format: https://github.com/WeAreDotnet/dotnet-creator-cards/blob/main/creator-cards/_creatorTemplate.json

# Welcome!

Welcome to https://www.wearedotnet.io

If you write about .NET or create .NET-related content, we are happy to have you here! 

We would love to add your content. Just make sure to follow our [Code of Conduct](https://github.com/wearedotnet/dotnet-creator-cards/blob/master/CODE_OF_CONDUCT.md)

You must add the full URL to your GitHub profile to your card, so we can assign it to the member account that used the same GitHub account for sign-up.

## Two Steps

To become a creator a card and a member account is required.
When your card has the GitHub URL of the account you have been using to sign-up we are going to link your account automatically to your card.

## #WeAreDonet Creator Submission Guidelines

* [ ] Make sure to follow our [Code of Conduct](https://github.com/wearedotnet/dotnet-creator-cards/blob/master/CODE_OF_CONDUCT.md) 

* [ ] We do not accept submissions with the sole intention of promoting a product or company.

* [ ]  We add you as a creator, not your company. 

* [ ]  The moderator team decides whether we accept or reject a submission.

### When Do We Accept Someone's Creator Card Submission? 

* [ ] You must have published at least three content pieces (long form content) since 2022 on any of your channels. 
* .NET itself
* .NET libraries and projects
* .NET languages C#, F#, Visual Basic
* Tools needed during development (for .NET)
* CI/CD
* Only in combination with .NET: SPA Frontend technologies like Angular, Vue.js, React etc. 
* Cloud services related to .NET applications (AWS, Azure...)


* [ ] There must be three content pieces in English. 

* [ ] There needs to be more than tweets. 

* [ ] Longer-form article on LinkedIn is good, but a self-hosted blog or one on a well-known platform like Hashnode, medium etc., is better. 

* [ ] Alternatively, you contributed with another form on a platform like YouTube, Twitch, Udemy or Pluralsight. If you have some recorded talks of conferences or anywhere else, that counts too! So in the form of a recorded video or a book. 

### RSS or Atom Feed 

* [ ] The content with feed.type = dotnet must be .NET related:
* .NET itself
* .NET libraries and projects
* .NET languages C#, F#, Visual Basic
* Tools needed during development (for .NET)
* CI/CD
* Only in combination with .NET: SPA Frontend technologies like Angular, Vue.js, React etc. 
* Cloud services related to .NET applications (AWS, Azure...)

* [ ] the content under feed.type = personal may contain off-topic posts.
* Project management
* leadership
* Other

* [ ] Submit an Atom or RSS URL inside your creator card that belongs to your blog 

* [ ] If you do not submit an RSS or Atom URL. We cannot consider your feed for the aggregation feature. 

### Content Guideline 

* [ ] If you have a self-hosted blog, please ensure you have a valid HTTPS certificate. 

* [ ] We host NO malicious or offensive content on the blog (including photos, swearing, etc.)

* [ ] You must add the full URL to your GitHub profile to your card, so we can assign it to the member account that used the same GitHub account for sign-up.

* [ ] My feed was sucessfully checked against this validator https://validator.w3.org/feed/
      
* [ ] The repository contains some cards based on an old file format. Please make sure to use the new format: https://github.com/WeAreDotnet/dotnet-creator-cards/blob/main/creator-cards/_creatorTemplate.json

## JSON Card Format

| Name         | Description                       |
| ------------ | --------------------------------- |
| name         | First and Lastname                |
| type         | CREATOR or MAINTAINER             |
| channels     | Max. 5 channels (Blog, Site etc.) |
| Feeds        | Max. 5 Feeds                      |

## Sample Card
```csharp
{
  "name": "FirstName LastName",
  "type": "CREATOR|MAINTAINER",
  "tags": ".NET, C#, ASP.NET",
  "github": "https://github.com/username",
  "channels": [
    {
      "name": "Blog|Site|Twitch|Youtube|Book|etc",
      "url": "https://www.wearedotnet.io/"
    }
  ],
  "feeds": [{
    "type": "personal|dotnet",
    "url": "https://...feeds/dotnet/rss.xml"
  }],
  "projects": [
    {
      "name": "Project Name",
      "description": "Project Description",
      "url": "https://github.com/<org>/project"
    }
  ]
}

```
