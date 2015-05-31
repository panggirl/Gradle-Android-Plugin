# Summary

* [译者序](README.md)
* [简介](introduction/introduction.md)
   * [新构建系统的目标](introduction/goals_of_the_new_build_system.md)
   * [为什么使用 Gradle?](introduction/why_gradle.md)
* [配置](requirements/requirements.md)
* [基础项目](basic_project/basic_project.md)
   * [构建文件示例](basic_project/simple_build_files.md)
   * [项目结构](basic_project/project_structure/project_structure.md)
       * [配置项目结构](basic_project/project_structure/configuring_the_structure.md)
   * [构建任务](basic_project/build_tasks/build_tasks.md)
       * [通用任务](basic_project/build_tasks/general_tasks.md)
       * [Java 项目的 Task](basic_project/build_tasks/java_project_tasks.md)
       * [Android Tasks](basic_project/build_tasks/android_tasks.md)
   * [基本的构建定制](basic_project/basic_build_customization/basic_build_customization.md)
       * [Manifest 属性](basic_project/basic_build_customization/manifest_entries.md)
       * [构建类型](basic_project/basic_build_customization/build_types.md)
       * [签名配置](basic_project/basic_build_customization/signing_configurations.md)
       * [运行 ProGuard](basic_project/basic_build_customization/running_proguard.md)
* [依赖、Library 和多项目](dependencies,android_libraries_and_multi-project_setup/dependencies,_android_libraries_and_multi-project_setup.md)
   * [依赖二进制包](dependencies,android_libraries_and_multi-project_setup/dependencies_on_binary_packages/dependencies_on_binary_packages.md)
       * [本地包依赖](dependencies,android_libraries_and_multi-project_setup/dependencies_on_binary_packages/local_packages.md)
       * [远程包依赖](dependencies,android_libraries_and_multi-project_setup/dependencies_on_binary_packages/remote_artifacts.md)
   * [多项目设置](dependencies,android_libraries_and_multi-project_setup/multi_project_setup.md)
   * [Library 项目](dependencies,android_libraries_and_multi-project_setup/library_projects/library_projects.md)
       * [创建 Library 项目](dependencies,android_libraries_and_multi-project_setup/library_projects/creating_a_library_project.md)
       * [普通项目和 Library 项目的区别](dependencies,android_libraries_and_multi-project_setup/library_projects/differences_between_a_project_and_a_library_project.md)
       * [引用 Library 项目](dependencies,android_libraries_and_multi-project_setup/library_projects/referencing_a_library.md)
       * [Library 项目发布](dependencies,android_libraries_and_multi-project_setup/library_projects/library_publication.md)
* [测试](testing/testing.md)
   * [单元测试](testing/unit_testing.md)
   * [基本知识和配置](testing/basics_and_configuration.md)
   * [运行测试](testing/running_tests.md)
   * [测试 Android Library 项目](testing/testing_android_libraries.md)
   * [测试报告](testing/test_reports/test_reports.md)
       * [独立项目](testing/test_reports/single_projects.md)
       * [多项目报告](testing/test_reports/multi-projects_reports.md)
   * [Lint 支持](testing/lint_support.md)
* [构建 Variants（变种）版本](build_variants/build_variants.md)
   * [产品定制](build_variants/product_flavors.md)
   * [构建类型+产品定制=构建变种版本](build_variants/build_type_+_product_flavor_=_build_variant.md)
   * [产品定制的配置](build_variants/product_flavor_configuration.md)
   * [源组件和依赖](build_variants/sourcesets_and_dependencies.md)
   * [构建和任务](build_variants/building_and_tasks.md)
   * [测试](build_variants/testing.md)
   * [多定制的变种版本](build_variants/multi-flavor_variants.md)
* [高级构建的自定义](advanced_build_customization/advanced_build_customization.md)
   * [构建选项](advanced_build_customization/build_options/build_options.md)
       * [Java 编译选项](advanced_build_customization/build_options/java_compilation_options.md)
       * [aapt 选项](advanced_build_customization/build_options/aapt_options.md)
       * [dex 选项](advanced_build_customization/build_options/dex_options.md)
   * [操作 task](advanced_build_customization/manipulating_tasks.md)
   * [构建类型和产物定制的属性引用](advanced_build_customization/buildtype_and_product_flavor_property_reference.md)
   * [使用sourceCompatibility 1.7](advanced_build_customization/using_sourcecompatibility_1.7.md)
