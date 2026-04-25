# Auth Platform

Centralized Authentication and Authorization using:
- Keycloak (OIDC / OAuth2)
- OpenFGA (Zanzibar-style ReBAC)
- Kubernetes + Helm
- Sonatype Nexus

## Realms
- internal-realm: employees with admin/editor/viewer roles
- external-realm: partners with partner/readonly roles

## Users
- alice: internal admin (owner)
- bob: internal viewer
- carol: external partner (editor)
- dave: external readonly (no access)
