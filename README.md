# Common Group References

To facilitate manuscript preparation and review, it is useful for us to have access to the same set of references and using a common naming convention. That is the purpose of this repository. By managing everything through git, we should be able to preserve fidelity over a reference list and avoid redundancy, etc. I will also be able to more closely monitor what literature is being cited and vice versa. 

## JabRef 

For managing the .bib, I strongly *strongly* advise that you use JabRef as a very nice reference manager. It used to be really great, but recently some functionality stopped working. It is really easy to add references via DOI or whatever. After you have it, you can download your own copy of group_references.bib, and then start adding your own references. 

*IMPORTANT* To make things consistent, please go to preferences --> Citation Key Generator, then change the 'Key Pattern' for two things:

1) Default pattern --> R:[year]_[auth]_[veryshorttitle]
2) Article --> R:[year]_[auth]_[veryshorttitle]

The purpose here is that we can have a good idea as to how to reference a particular article within LaTeX using this coding. 'R' sets off that this is a reference, and then the rest picks out which article we care about. 
