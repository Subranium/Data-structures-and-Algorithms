# 遍历算法

## 先序遍历

先序遍历算法流程如下：

1. 访问根结点
2. 先序遍历左子树
3. 先序遍历右子树

{% tabs %}
{% tab title="递归方式" %}
```text
func Preorder(node *TreeNode){
	if node != nil{
		fmt.Printf("%s\n", node.Val)
		PreShowTree(node.Left)
		PreShowTree(node.Right)
	}
}
```
{% endtab %}

{% tab title="非递归方式" %}
```

```
{% endtab %}
{% endtabs %}

## 中序遍历

## 后序遍历

## 层次遍历

