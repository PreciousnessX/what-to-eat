# 日常菜谱管理

这是一个用于管理日常菜谱的项目，帮助记录和规划每日饮食。通过积累丰富的菜谱知识库，未来可以实现借助Cursor或者Trae自动生成每周菜谱的功能，让饮食规划更加便捷。

## 项目结构

- `备用库.md` - 收录各类菜品的制作方法，按照荤素分类整理
  - 荤菜：猪肉、牛肉、鸡肉等
  - 素菜：菌菇类、时令蔬菜等
- `YYYY.MM.DD.md` - 每周菜谱规划（如：2025.3.19.md代表2025.3.19的下一周的食谱），包含：
  - 周一至周日的午餐和晚餐安排
  - 每日菜品搭配建议
  - 本周食材采购清单


## 文件格式规范

### 备用库格式

```markdown
# 菜谱备用库
## 分类（荤菜/素菜）
### 子分类（如：猪肉🐷/菌菇类🍄）
- 菜品名称：主要食材1、食材2、食材3
```

### 每日菜谱格式

```markdown
### 早餐/午餐/晚餐
1. 菜品1 + 配菜：所需食材
2. 菜品2：所需食材

* 需购素菜：食材1、食材2
* 需购荤菜：食材1、食材2
* 其他：调味料等

家中已有：现有食材列表
```

## 使用说明

1. 查看菜品：打开`备用库.md`，可以按照分类浏览所有可制作的菜品
2. 规划菜单：
   - 创建每周菜谱文件（如`2024.12.md`），规划一周的午餐和晚餐
   - 创建当日日期的md文件（如`2024.3.27.md`），按照格式填写当日菜单
3. 更新菜谱：在`备用库.md`中添加新的菜品，按照已有格式进行分类记录
4. 采购清单：在每日菜谱文件中记录需要采购的食材，并标注家中已有的食材，避免重复购买

## 注意事项

- 添加新菜品时注意按照正确的分类和格式
- 规划菜单时注意参考家中现有食材
- 及时更新家中库存食材信息
- 持续丰富备用库，为未来实现自动生成菜谱打好基础