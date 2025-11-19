+++
title = ""
menu = "main"
weight = 1
+++

# The RBAC Wall of Shame

 A list of vendors that treat finer-grained access control as a luxury feature, not a core security requirement.

{{< details "Why is this important?" >}}

Role-based access control (RBAC) is a mechanism for restricting data access and actions based on the roles of individual users within an organization.

For organizations with more than a handful of employees, granular access control on the services they use is critical for security and compliance.
It enables organisations to apply the principle of least privilege in the real world, reducing the risk of accidental or malicious data breaches.

Without proper RBAC, organizations are forced to either:
- Give all users admin access (creating significant security risks), or
- Maintain a flat permission structure where everyone has the same access level, or
- Purchase expensive "Enterprise" tiers to access basic security features

In short: RBAC is a core security requirement for any company serious about their users' data.

SaaS vendors appear not to have received this message, however.
Fine-grained access control is often only available as part of "Enterprise" or "Premium" pricing tiers, which assume either a huge number of users (minimum seat count) or are force-bundled with other features which may have no value to the company using the software.

If companies claim to "take your security seriously", then RBAC should be available as a feature that is either:
- Part of the core product, or
- An optional paid extra for a reasonable delta, or
- Attached to a price tier, but with a reasonably small gap between basic and RBAC-enabled tiers

Many vendors charge 2x, 3x, or 4x the base product pricing for access to proper RBAC, which disincentivizes its use and encourages poor security practices.

{{< /details >}}

# The List

{{< vendor-table >}}

&nbsp;

[➕ Add vendor](https://github.com/secure-engineer/rbac-tax/issues/new?template=add-bad-vendor.md)

&nbsp;

---

# FAQs

{{< details "How is base pricing determined?" >}}
We disregard free tier pricing, as we can assume these aren't intended for long term business customer use. We also disregard "single person" pricing, under the assumption that we're looking on behalf of a team of 5, 10, or more people.
{{< /details >}}

<br>

{{< details "How is RBAC pricing determined?" >}}
This is dependent on the cheapest tier supporting access control that is more advanced than "user and admin".
{{< /details >}}

<br>

{{< details "This doesn't scale linearly for number of seats!" >}}
Correct. Since we don't know who's reading the page, it's easiest to just assume a team with no volume discount.
{{< /details >}}

<br>

{{< details "I'm a vendor and this data is wrong!" >}}
Please feel free to submit a PR to this page. I only want this data to be accurate.
{{< /details >}}

<br>

{{< details "I'm a vendor and this doesn't reflect the value-add of our Enterprise tier!" >}}
That's the point. Decouple your security features from your value-added services. They should be priced separately.
{{< /details >}}

<br>

{{< details "But it costs money to provide an RBAC feature, so we can't offer it for free!" >}}
While I'd like people to really consider it a *bare minimum* feature for business SaaS, I'm OK with it costing a little extra to cover maintenance costs. If your RBAC support is a 10% price hike, you're not on this list. But these percentage increases are not maintenance costs, they're revenue generation because you know your customers have no good options.
{{< /details >}}

&nbsp;
