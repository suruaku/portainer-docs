# Add a ConfigMap

From the menu select **ConfigMaps & Secrets** then click **Add with form**.&#x20;

{% hint style="info" %}
ConfigMaps can also be added [using a manifest](../applications/manifest.md) by clicking **Create from manifest**.
{% endhint %}

<figure><img src="../../../.gitbook/assets/2.15-k8s_kubernetes_configmap_create_form.gif" alt=""><figcaption></figcaption></figure>

Define the ConfigMap, using the table below as a guide.

| Field/Option       | Overview                                                                                                                                                                               |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Name               | Give the ConfigMap a descriptive name.                                                                                                                                                 |
| Namespace          | Select the namespace where the ConfigMap will be saved.                                                                                                                                |
| Configuration type | Select **ConfigMap** from the dropdown. ConfigMaps should not store any sensitive information. If you need to store sensitive information consider using a [secret](add-1.md) instead. |

<figure><img src="../../../.gitbook/assets/2.15-kubernetes_configmap_add_form_config.png" alt=""><figcaption></figcaption></figure>

In the **Data** section you can enter the details of your ConfgMap, in either **Simple mode** or **Advanced mode**. Under Simple mode you can add entries in a key and value format, and in Advanced mode you can paste in multiple values in YAML format.

<figure><img src="../../../.gitbook/assets/2.15-kubernetes_configmap_add_form_config_data.png" alt=""><figcaption><p>Adding data in Simple mode</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/2.15-kubernetes_configmap_add_from_config_data_simple.png" alt=""><figcaption><p>Adding data in Advanced mode</p></figcaption></figure>

When you have finished defining the ConfigMap, click **Create ConfigMap.**
