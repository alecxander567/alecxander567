<div align="center">

# {{user.name}}

{{user.bio}}

**Location:** {{user.location}} &nbsp;|&nbsp; **Company:** {{user.company}} &nbsp;|&nbsp; **Blog:** {{user.blog}}

</div>

---

## GitHub Stats

![GitHub Stats]({{stats_card_url}})

### Activity Summary

| Metric | Count |
|---|---|
| Total Repositories | {{stats.total_repos}} |
| Total Stars Received | {{stats.total_stars}} |
| Total Forks | {{stats.total_forks}} |
| Public Repos | {{stats.public_repos}} |
| Private Repos | {{stats.private_repos}} |

### Top Languages

{{languages.top_5}}

### Recent Activity (Last 30 Days)

| Type | Count |
|---|---|
| Commits | {{contributions.last_30_days.commits}} |
| Pull Requests | {{contributions.last_30_days.prs}} |
| Issues | {{contributions.last_30_days.issues}} |

---

<div align="center">

From [{{user.username}}](https://github.com/{{user.username}})

_Last updated: {{current_date}}_

</div>
