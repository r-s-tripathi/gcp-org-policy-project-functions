## constraints/cloudfunctions.owedIngressSettings
### This list constraint defines the allowed ingress settings for deployment of a Cloud Function. When this constraint is enforced, functions will be required to have ingress settings that match one of the allowed values. By default, Cloud Functions can use any ingress settings. Ingress settings must be specified in the allowed list using the values of the IngressSettings enum.

## constraints/cloudfunctions.owedVpcConnectorEgressSettings 
### This list constraint defines the allowed VPC Connector egress settings for deployment of a Cloud Function. When this constraint is enforced, functions will be required to have VPC Connector egress settings that match one of the allowed values. By default, Cloud Functions can use any VPC Connector egress settings. VPC Connector egress settings must be specified in the allowed list using the values of the VpcConnectorEgressSettings enum.

## constraints/cloudfunctions.requireVPCConnector
### This boolean constraint enforces setting a VPC Connector when deploying a Cloud Function. When this constraint is enforced, functions will be required to specify a VPC Connector. By default, specifying a VPC Connector is not required to deploy a Cloud Function.
