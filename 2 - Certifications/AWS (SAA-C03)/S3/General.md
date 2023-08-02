
## Buckets
Globally unique name (across all regions an accounts)

### Naming Convention
- No uppercase
- No underscore
- Starts with uppercase or number
- No IP address
- 1-63 characters long
- Must NOT start with the prefix xn--
- Must NOT start with the suffix -s3alias

## Objects
They are files


Versioning -> Properties

Delete file (Delete marker)

Restore file (delete "delete marker")

Replication -> Replication Rules
CRR (Cross Region Replication) - SRR (Same Region Replication)
The replication will only replicate objects starting from the activation, however, existing objects can be transferred by choosing to perform a batch operation at the replication step
You need to enable delete marker replication manually