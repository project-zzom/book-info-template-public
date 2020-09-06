---
layout: default
---
## 베타 리더

도움을 주신 모든 베타 리더님 감사합니다.

{% for beta-reader in site.data.beta-readers %}* {{ beta-reader.name }} / {{ beta-reader.role }}
{% endfor %}