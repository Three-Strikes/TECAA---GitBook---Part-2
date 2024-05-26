# What is it?

This API documentation smell can be identified by long and verbose text that describes a single API element. These elements can be any part of an API, be them endpoints or examples inside of those endpoints.

This smell often causes the API documentation to become unusable, because it's:

1. Slow and hard to read;
2. Has too much information to parse at once, for one element, making it difficult to follow;
3. It is hard to make an alteration, given how frequent APIs can change, making it unmaintainable.

If your documentation suffers from these problems, you might want to try and scale back the information you provide about your API, or trim it to only the absolutely necessary.

### References

{% embed url="https://arxiv.org/pdf/2102.08486" %}
Reference 1
{% endembed %}

{% embed url="https://ieeexplore.ieee.org/abstract/document/7140676" %}

