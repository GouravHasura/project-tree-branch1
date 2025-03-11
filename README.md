# project-tree-branch1

1.  ddn subgraph init branch1
2. ddn subgraph add --subgraph app/subgraph.yaml  --target-supergraph ./supergraph.yaml 
3. ddn project subgraph create app --project elegant-viper-5629

4.  ddn connector init -i --subgraph app/subgraph.yaml
5.  ddn connector introspect mypostgres --subgraph app/subgraph.yaml
6.

    ddn model add mypostgres "*" --subgraph app/subgraph.yaml
    ddn command add mypostgres "*" --subgraph app/subgraph.yaml
    ddn relationship add mypostgres "*" --subgraph app/subgraph.yaml

7. ddn supergraph build create