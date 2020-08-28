# SensitiveWordsFilter
Filter

# 效果：
    if __name__ == '__main__':
    str='我操，这打野真垃圾，真废物！'
    Filter=SensitiveFilter()
    replaceStr=Filter.replaceSensitiveWord(str)
    print(replaceStr) #  **，这打野真垃圾，真**！
