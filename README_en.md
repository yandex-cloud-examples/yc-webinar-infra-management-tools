# Webinar: Infrastructure management tools in Yandex Cloud

This webinar will introduce you step by step to the tools you can use to develop complex applications or services within the Yandex Cloud (YC) infrastructure.

The webinar materials combine theoretical insights and hands-on assignments.

After going through the theoretical part of a topic, you will be required to complete some hands-on tasks.
Each tool has its own dedicated folder in the repository, prefixed with `lab`. Inside each folder, there is a `README.md` file with detailed guidance and command sections that you can click to copy and then paste into the terminal.


## Deployment
```bash
git clone https://github.com/yandex-cloud/yc-architect-solution-library.git
cp -r yc-architect-solution-library/demos/yc-infra-management/ labs/
cd labs
```

## List of hadns-on assignments

1. [Cloud web console (Web UI)](./lab-01-ui/README.md)
2. [Yandex Cloud CLI (yc)](./lab-02-yc/README.md)
3. [Terraform](./lab-03-terraform/README.md)
4. [Crossplane](./lab-04-crossplane/README.md)
5. [Pulumi](./lab-05-pulumi/README.md)

To meet the workshop purpose, within the first hands-on assignment, we will deploy a virtual machine from the [Yandex Cloud Toolbox](https://cloud.yandex.ru/marketplace/products/yc/toolbox) image available in [Yandex Cloud Marketplace](https://cloud.yandex.ru/marketplace).

Now, let’s proceed to [hands-on assignment 1>>](./lab-01-ui/README.md)
